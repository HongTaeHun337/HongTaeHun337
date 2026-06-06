# 👋 Hong Tae Hun — Backend Developer

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=4F8EF7&center=true&vCenter=true&width=500&lines=Backend+Developer;Oracle+DB+%7C+Java+%7C+Spring;Data+Modeling+%26+Real-time+Service" alt="Typing SVG" />
</p>

> *데이터 무결성과 실시간 서비스 구현에 관심이 많은 백엔드 개발자입니다.*  
> *"왜 이 기술을 선택했는가"를 항상 고민하며 개발합니다.*

---

## 🧑‍💻 About Me

| 항목 | 내용 |
|------|------|
| 🎓 전공 | 서일대학교 소프트웨어공학 |
| 📜 자격증 | 정보처리산업기사 · 컴퓨터활용능력 1급 *(2026년 하반기 취득/응시 예정)* |
| 🔗 GitHub | [HongTaeHun337](https://github.com/HongTaeHun337) |
| 💡 관심 분야 | 백엔드 API 설계, DB 모델링, 실시간 서비스 |

---

## 🛠 Tech Stack

**Backend**  
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=spring&logoColor=white)
![MyBatis](https://img.shields.io/badge/MyBatis-000000?style=flat-square&logoColor=white)

**Database**  
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)

**Frontend**  
![JSP](https://img.shields.io/badge/JSP-007396?style=flat-square&logo=java&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)

---

## 💼 Projects

---

### ✈️ TripTo — 여행 동행 매칭 플랫폼

> 혼자 여행하는 사람들이 취향과 일정이 맞는 동행자를 찾고, 실시간으로 소통할 수 있는 여행 커뮤니티 웹 서비스

**기술 스택**  
`Java 11` `Spring Framework 5.3.9` `Spring Security` `MyBatis` `WebSocket` `Oracle DB` `HikariCP` `Cloudinary` `JSP`

<details>
<summary>📌 주요 기술 선택 이유</summary>

| 기술 | 도입 이유 |
|------|-----------|
| **WebSocket** | HTTP 요청-응답 구조의 한계를 넘어, 서버-클라이언트 간 **양방향 실시간 통신**으로 지연 없는 1:1 및 다대다 채팅 환경 제공 |
| **HikariCP** | 커넥션 생성/종료 오버헤드 제거, Connection Pool 사전 생성으로 **쿼리 응답 속도 최적화** |

</details>

**💡 나의 기여**

| 역할 | 내용 |
|------|------|
| 동적 매칭 쿼리 | 성별·연령·여행지·기간·스타일 등 **5개 이상 다중 조건** 대응 MyBatis `<if>`, `<choose>` 동적 쿼리 구현 → Full Table Scan 방지 및 검색 응답 속도 개선 |
| 실시간 채팅 구현 | `spring-websocket` 기반 채팅 채널 구축, 메시지 DB 저장 로직 작성 |

> 🔧 **Troubleshooting — WebSocket 동시성 문제**  
> 다수 사용자 동시 접속/퇴장 시 세션 정보 충돌로 메시지 오전송 현상 발생  
> → 세션 정보를 **`ConcurrentHashMap`** 으로 관리하여 Thread-Safe 동기화 달성, 안정성 확보

---

### 🎬 씨네21 DB 모델링 — 영화 정보 관리 RDBMS 설계

> 국내 최대 영화 포털 씨네21을 벤치마킹한 대규모 DB 아키텍처 설계 프로젝트

**기술 스택**  
`Oracle DB` `eXERD` `SQL Developer` `DDL / DML`

**💡 나의 기여**

| 역할 | 내용 |
|------|------|
| N:M 관계 정규화 | 영화-배우, 영화-장르 다대다 관계를 매핑 테이블로 해소 → **18개 핵심 테이블 + 20개 시퀀스** 구성의 실무 수준 스키마 설계 |
| 리뷰 구조 분리 | 일반 관람객 별점 ↔ 전문가 심층 비평 데이터 구조 분리 → 조회 시 병목 방지 및 확장성 확보 |
| 더미 데이터 구축 | 개봉작 20여 편 기반 **더미 데이터 100건 이상** DML 작성, SEQUENCE + FK 연동으로 **데이터 무결성 오류 0% 달성** |

**📊 ERD 설계도**

| 논리 설계도 | 물리 설계도 |
|:-----------:|:-----------:|
| ![논리 ERD](./Sine21-main/logical_erd.png) | ![물리 ERD](./Sine21-main/physical_erd.png) |

---

### 📅 Deverytime — 학습 일정 관리 웹 애플리케이션

> 학생·수험생의 체계적인 학습 일정 수립과 진척도 관리를 지원하는 MVC 기반 웹 서비스

**기술 스택**  
`Java` `JSP` `Servlet` `JDBC` `Apache Tomcat` `HTML/CSS/JavaScript`

**💡 나의 기여**

| 역할 | 내용 |
|------|------|
| 스케줄러 CRUD | 날짜·시간대별 학습 계획 등록/조회/수정/삭제 비즈니스 로직 및 DAO 패턴 적용 |
| 캘린더 UI | JSP 기반 캘린더 뷰 설계 및 데이터 연동 |

> 🔧 **Troubleshooting — 일정 중복 등록 문제**  
> 이미 등록된 시간대에 중복 일정 삽입 가능 → 데이터 무결성 훼손  
> → INSERT 전 기존 일정의 시작/종료 시간과 **겹치는지 검증하는 SELECT 쿼리**를 선행 실행하도록 수정, 중복 등록 원천 차단  
> → **배운 점:** 프론트엔드 유효성 검사만으로는 부족하며, 백엔드 레이어에서의 철저한 데이터 Validation이 필수임을 체감

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=HongTaeHun337&show_icons=true&theme=tokyonight&hide_border=true" height="160"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=HongTaeHun337&layout=compact&theme=tokyonight&hide_border=true" height="160"/>
</p>

---

<p align="center">
  <i>읽어주셔서 감사합니다 🙏</i>
</p>
