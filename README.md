<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=Han%20Yugyeong&fontSize=58&fontColor=fff&animation=fadeIn&fontAlignY=38&desc=Web%20Developer%20%7C%20Java%20%7C%20Spring%20Boot%20%7C%20Vue%203&descAlignY=60&descSize=18" width="100%" />

<div align="center">

[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:amie.hyk@gmail.com)
[![Blog](https://img.shields.io/badge/Tech%20Blog-222222?style=flat-square&logo=githubpages&logoColor=white)](https://funhappyit.github.io/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/funhappyit)

</div>

## About Me

사용자에게 안정적으로 전달되는 서비스를 만드는 웹 개발자입니다. Java·Spring Boot 기반의 백엔드와 Vue 3·React 기반의 프론트엔드를 함께 구현합니다.

ERP/MES 시스템 개발 경험을 바탕으로 요구 사항을 서비스 구조로 구체화하는 데 익숙합니다. 개인 프로젝트에서는 동시성 문제, Redis 캐싱, 실시간 통신, 클라우드 배포처럼 운영 환경에서 마주하는 문제를 직접 설계하고 검증하고 있습니다.

## Featured Projects

### 💬 [chat-notify](https://github.com/funhappyit/chat-notify)

실시간 채팅과 읽지 않은 메시지 알림을 제공하는 서비스입니다. 여러 서버 인스턴스에서도 메시지를 일관되게 전달할 수 있도록 Redis Pub/Sub 기반 브로드캐스팅을 적용하고, Access/Refresh JWT로 인증 흐름을 구성했습니다.

[![Frontend](https://img.shields.io/badge/Frontend-Live-6366F1?style=flat-square&logo=vercel&logoColor=white)](https://chat-notify.vercel.app)
[![Backend API](https://img.shields.io/badge/Backend%20API-Live-00C7B7?style=flat-square&logo=render&logoColor=white)](https://chat-notify.onrender.com)

| 구분 | 내용 |
| --- | --- |
| Backend | Spring Boot 3.x · Java 21 · Spring WebSocket/STOMP · SSE · JWT |
| Frontend | React 18 · TypeScript · Vite |
| Infra | Render · Vercel · Aiven (MySQL) · Upstash (Redis) |
| 핵심 구현 | Redis Pub/Sub 다중 서버 브로드캐스팅 · SSE 읽지 않은 메시지 알림 · Access/Refresh JWT 이중 토큰 인증 |

### 🧩 [puzzle-leaderboard](https://github.com/funhappyit/puzzle-leaderboard)

동시에 많은 점수 갱신 요청이 발생하는 퍼즐 게임 랭킹 API입니다. 순위 조회에는 Redis ZSET을 사용하고, 점수 갱신 과정에서 발생할 수 있는 Race Condition을 Redisson 분산 락으로 제어했습니다.

[![Frontend](https://img.shields.io/badge/Frontend-Live-6366F1?style=flat-square&logo=vercel&logoColor=white)](https://puzzle-leaderboard-five.vercel.app)
[![Backend API](https://img.shields.io/badge/Backend%20API-Live-00C7B7?style=flat-square&logo=render&logoColor=white)](https://puzzle-leaderboard-jg58.onrender.com/api/v1/rankings?puzzleId=wordle-ko)

| 구분 | 내용 |
| --- | --- |
| Backend | Spring Boot 3.4 · Java 21 · MySQL · Redisson · Flyway |
| Frontend | React 18 · TypeScript · Vite |
| Infra | Render · Vercel · Aiven · Upstash · GitHub Actions |
| 핵심 구현 | Redisson 분산 락으로 Race Condition 방지 · Redis ZSET 랭킹 · JMeter 부하 테스트 |

| 테스트 방식 | TPS | 응답 시간 |
| --- | ---: | ---: |
| 락 없음 | 740.7/sec | 31ms |
| Redis `ZINCRBY` | 816.3/sec | 25ms |
| Redisson 분산 락 | 286.9/sec | 232ms |

## Tech Stack

<div align="center">

[![Skills](https://skillicons.dev/icons?i=java,js,ts,spring,redis,hibernate&theme=dark)](https://skillicons.dev)

[![Skills](https://skillicons.dev/icons?i=vue,react,vite,tailwind,pinia,sass&theme=dark)](https://skillicons.dev)

[![Skills](https://skillicons.dev/icons?i=mariadb,mysql,oracle,docker,githubactions&theme=dark)](https://skillicons.dev)

</div>

| 분야 | 기술 |
| --- | --- |
| Language | Java · JavaScript · TypeScript |
| Backend | Spring Boot · Spring Security · JPA/Hibernate · Flyway |
| Frontend | Vue 3 · React 18 · Rsbuild · Vite · Pinia · Tailwind CSS |
| Cache / Concurrency | Redis (ZSET · Rate Limiting) · Redisson 분산 락 |
| Database | MariaDB · MySQL · Oracle · MSSQL |
| Infra / Test | Docker · GitHub Actions · Jenkins · JMeter |

## GitHub Stats

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=funhappyit&theme=radical&hide_border=true&date_format=Y.n.j)](https://git.io/streak-stats)

![](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=funhappyit&theme=radical)

</div>

## 🎀 My Buddy

<div align="center">

<table>
  <tr>
    <td align="center" width="160">
      <img src="https://avatars.githubusercontent.com/u/220837603?v=4" width="120" /><br />
      <b>헬로키티 / Hello Kitty</b><br />
      <sub>🎀 Sanrio · Since 1974</sub>
    </td>
    <td align="left" valign="top">
      <br />
      <b>기술</b><br />
      &nbsp;🎀 백엔드 — Spring Boot<br />
      &nbsp;💚 프론트엔드 — Vue 3<br />
      &nbsp;⚡ 캐싱 — Redis<br />
      &nbsp;🛡️ 동시성 제어 — Redisson 분산 락<br />
      &nbsp;💥 부하 테스트 — JMeter<br />
      <br />
      <b>타입</b> : 리본 / Web
    </td>
  </tr>
</table>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer" width="100%" />
