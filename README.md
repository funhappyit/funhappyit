<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=Han%20YuKjoung&fontSize=60&fontColor=fff&animation=fadeIn&fontAlignY=38&desc=Backend%20Developer%20%7C%20Java%20%2F%20Kotlin%20%7C%20Spring%20Boot&descAlignY=60&descSize=18" width="100%"/>

<div align="center">

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Ffunhappyit&count_bg=%236366F1&title_bg=%23111827&icon=github&icon_color=%23fff&title=visitors&edge_flat=true)](https://hits.seeyoufarm.com)
[![Gmail](https://img.shields.io/badge/amie.hyk@gmail.com-EA4335?style=flat-square&logo=Gmail&logoColor=white)](mailto:amie.hyk@gmail.com)
[![Blog](https://img.shields.io/badge/Tech_Blog-03C75A?style=flat-square&logo=naver&logoColor=white)](https://blog.naver.com/winterkjoung/)

> *"We are what we repeatedly do. Excellence, then, is not an act but a habit."* — Aristotle

</div>

---

## 👨‍💻 About Me

엔터프라이즈 백엔드 개발자로 **Java / Kotlin + Spring Boot** 기반 서버 개발을 주로 합니다.

현재는 단순 CRUD를 넘어 **동시성 제어 · Redis 캐싱 · 클라우드 네이티브 배포** 역량을 포트폴리오로 증명하는 중입니다.  
JMeter 부하 테스트로 race condition을 수치로 증명하고, 분산락 적용 전/후 TPS를 비교·기록합니다.

---

## 🛠 Tech Stack

**Language**

![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=Kotlin&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=black)

**Backend**

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![JPA](https://img.shields.io/badge/JPA_Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Redisson](https://img.shields.io/badge/Redisson-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=for-the-badge&logo=flyway&logoColor=white)

**Database**

![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![MSSQL](https://img.shields.io/badge/MSSQL-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)

**Infra / DevOps**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![JMeter](https://img.shields.io/badge/JMeter-D22128?style=for-the-badge&logo=apachejmeter&logoColor=white)

**AI Tools (with Claude)**

![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![GitHub Copilot](https://img.shields.io/badge/GitHub_Copilot-000000?style=for-the-badge&logo=github&logoColor=white)
![IntelliJ](https://img.shields.io/badge/IntelliJ_IDEA-000000?style=for-the-badge&logo=intellijidea&logoColor=white)

---

## 💼 Career

| 구분 | 기간 | 내용 | 소속 |
|:----:|:----:|------|:----:|
| 🏢 재직 | 2025.07 ~ 현재 | 웹 개발 | **AMIESOFT** |
| 🏢 재직 | 2020.07 ~ 2025.07 | 보안 웹 개발 | SECULAYER |
| 📚 교육 | 2019.10 ~ 2020.06 | SW 엔지니어링 과정 | 대덕 HRD 센터 |
| 🎓 학력 | 2015.03 ~ 2019.08 | 전자제어공학과 | 한밭대학교 |

---

## 🚀 Portfolio

### 🧩 [puzzle-leaderboard](https://github.com/funhappyit/puzzle-leaderboard)

> 실시간 퍼즐 게임 랭킹 API 서버 — 동시성 제어 · Redis 캐싱 · 클라우드 배포 역량 증명 프로젝트

| 항목 | 내용 |
|------|------|
| **Stack** | Kotlin · Spring Boot 3.4 · MariaDB · Redis · Docker |
| **동시성** | Redisson 분산락으로 race condition 제거 |
| **캐싱** | Redis Sorted Set(ZSET)으로 O(log N) 랭킹 조회 |
| **Rate Limiting** | Redis INCR + EXPIRE 슬라이딩 윈도우 |
| **부하 테스트** | JMeter 1,000 동시 요청 — 분산락 전/후 TPS 비교 |
| **배포** | AWS ECS Fargate + GitHub Actions CI/CD + Terraform |

| 케이스 | TPS | 평균 응답시간 | 오류율 |
|--------|:---:|:----------:|:-----:|
| 락 없음 (DB) | - | - | - |
| Redis ZINCRBY | - | - | - |
| Redisson 분산락 | - | - | - |

> 📌 3주차 JMeter 부하 테스트 완료 후 수치 업데이트 예정

---

## 🤖 Claude와 함께한 작업들

| 도구 | 활용 사례 |
|------|----------|
| **Claude Code** | 프로젝트 설계 · 코드 리뷰 · 리팩토링 · 이슈 작성 자동화 |
| **GitHub CLI (gh)** | 이슈·PR 생성 자동화, 레포 관리 |
| **Docker Compose** | MariaDB + Redis 로컬 인프라 구성 |
| **Flyway** | DB 마이그레이션 스크립트 설계 |
| **JMeter** | 부하 테스트 시나리오 설계 (진행 중) |
| **Terraform** | AWS 인프라 IaC 구성 (진행 중) |

---

## 📊 GitHub Stats

<div align="center">

![funhappyit's GitHub stats](https://github-readme-stats.vercel.app/api?username=funhappyit&show_icons=true&theme=radical&hide_border=true&bg_color=0D1117)
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=funhappyit&layout=compact&theme=radical&hide_border=true&bg_color=0D1117)](https://github.com/funhappyit)

</div>

---

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer" width="100%"/>
