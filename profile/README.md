<!-- 상단 웨이브 배너 -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=180&section=header&text=TrendChat&fontSize=40&fontColor=ffffff&fontAlignY=35&desc=&descAlignY=60&descAlign=63" />
</p>


<h2 align="center">👥 Team Members</h2>

<table align="center">
  <tr>
    <td align="center">
      <img src="https://github.com/tae98.png" width="100"/><br/>
      <strong>김태현</strong><br/>
      Cho<br/>
      <a href="https://github.com/tae98">@tae98</a>
    </td>
    <td align="center">
      <img src="https://github.com/doolchong.png" width="100"/><br/>
      <strong>이건</strong><br/>
      Gall<br/>
      <a href="https://github.com/doolchong">@doolchong</a>
    </td>
    <td align="center">
      <img src="https://github.com/pookyspooky.png" width="100"/><br/>
      <strong>홍성현</strong><br/>
      Dr.Mundo<br/>
      <a href="https://github.com/pookyspooky">@pookyspooky</a>
    </td>
  </tr>
</table>

## 📝 프로젝트 개요
**📆 개발 기간:** 2024.05.19 ~ 2024.07.22 

**트렌드챗**은 실시간으로 인기 주제를 중심으로 사람들이 모여 대화할 수 있는  **토픽 기반 단체 채팅 플랫폼**입니다.  Kafka, Redis, WebFlux, RabbitMQ 등 최신 기술을 활용해 고성능 실시간 처리를 구현했으며,  모든 서비스는 마이크로서비스 구조로 나누어 Docker로 컨테이너화되어 운영됩니다.

<h2 align="center">🧱 Tech Stack</h2>

<p align="center">
  <!-- Backend -->
  <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/SpringBoot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white" />
  <img src="https://img.shields.io/badge/Kafka_Connect-000000?style=for-the-badge&logo=apachekafka&logoColor=white" />
  <img src="https://img.shields.io/badge/Kafka_UI-9146FF?style=for-the-badge&logo=graphql&logoColor=white" />
  <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
</p>

<p align="center">
  <!-- Frontend -->
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" />
</p>

<p align="center">
  <!-- Monitoring -->
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" />
  <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" />
  <img src="https://img.shields.io/badge/Zipkin-000000?style=for-the-badge&logo=openzipkin&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
</p>

## ✅ 서비스 플로우

1️⃣ **채팅방 자동 생성**  
   실시간으로 수집한 **구글 인기 검색어**를 기반으로  
   새로운 채팅방이 자동 생성되며,  
   제목과 설명은 AI Agent가 주제에 맞게 작성합니다.

2️⃣ **채팅방 입장 및 참여**  
   사용자는 관심 있는 주제의 채팅방에 자유롭게 입장해  
   실시간으로 대화를 주고받을 수 있습니다.

3️⃣ **메시지 송수신**  
   WebFlux 기반 SSE(Server-Sent Events)와  
   **RabbitMQ + Redis Pub/Sub** 구조를 활용하여  
   메시지를 안정적으로 브로드캐스트하며,  
   모든 참여자에게 실시간으로 전달됩니다.

4️⃣ **트렌드 분석 및 인기 채팅방 노출**  
   채팅방별 참여자 수 및 메시지량을 분석해  
   실시간 인기 채팅방을 집계하고 메인 화면에 노출합니다.

5️⃣ **알림 및 트렌드 변화 표시**  
   새로운 메시지가 도착하면 해당 채팅방에  **NEW** 표시가 나타나고,  
   트렌드 변화가 감지되면 관련 알림이 상단 🔔 알림 바에 표시됩니다.



<!-- Footer 웨이브 -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=120&section=footer" />
</p>
