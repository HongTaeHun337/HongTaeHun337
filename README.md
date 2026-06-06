# 👋 Hong Tae Hun — Backend Developer

> *Oracle DB와 Java 백엔드를 중심으로, 데이터 모델링과 실시간 서비스 구현에 관심이 많은 개발자입니다.*

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=4F8EF7&center=true&vCenter=true&width=435&lines=Backend+Developer;Oracle+DB+%7C+Java+%7C+Spring;Data+Modeling+Enthusiast" alt="Typing SVG" />
</p>

---

## 🧑‍💻 About Me

| 항목 | 내용 |
|------|------|
| 🎓 전공 | 서일대학교 소프트웨어공학 |
| 📜 자격증 | 정보처리산업기사, 컴퓨터활용능력 *(취득 예정)* |
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

**팀 주요 기능**
- Spring Security 기반 인증/인가 및 이메일 인증 회원가입 (JavaMail)
- 다중 이미지 업로드 여행 기록 게시판 및 댓글 시스템
- 관리자 대시보드, 불량 사용자 신고, 맞춤형 게시물 추천

**💡 나의 기여**

| 역할 | 내용 |
|------|------|
| 매칭 시스템 | 일정·여행지·성향 조건 기반 동행자 매칭 로직 설계 및 MyBatis 동적 SQL 구현 |
| 실시간 채팅 | `spring-websocket`을 활용한 채팅 채널 구현, 세션 관리 및 메시지 DB 저장/불러오기 |

> 💬 *WebSocket을 선택한 이유: 매칭 직후 즉각적인 소통이 필요한 UX를 위해 polling 방식 대신 양방향 실시간 통신 채택*

---

### 🎬 씨네21 DB 모델링 — 영화 정보 관리 RDBMS 설계

> 국내 최대 영화 포털 씨네21의 데이터 구조를 벤치마킹한 대규모 DB 아키텍처 설계 프로젝트

**기술 스택**

`Oracle DB` `eXERD` `SQL Developer` `DDL / DML`

**팀 주요 기능**
- 18개 핵심 테이블 + 20개 시퀀스 구성의 실무 수준 스키마 설계
- 영화·감독·배우·스태프·시놉시스·리뷰 메타데이터 통합 구조

**💡 나의 기여**

| 역할 | 내용 |
|------|------|
| N:M 관계 정규화 | 영화-배우, 영화-장르 다대다 관계를 매핑 테이블로 해소, 물리 모델 반영 |
| 리뷰 구조 분리 설계 | 일반 관람객 별점 시스템 ↔ 전문가 심층 비평 데이터 구조 분리로 무결성·확장성 확보 |
| 더미 데이터 구축 | 실제 개봉작 20여 편 기반 DML 작성, SEQUENCE + FK 연동으로 데이터 무결성 검증 |

> 📌 *ERD 다이어그램은 프로젝트 내 `/docs/erd.png` 참고*

---

### 📅 Deverytime — 학습 일정 관리 웹 애플리케이션

> 학생·수험생의 체계적인 학습 일정 수립과 진척도 관리를 지원하는 MVC 기반 웹 서비스

**기술 스택**

`Java` `JSP` `Servlet` `JDBC` `Apache Tomcat` `HTML/CSS/JavaScript`

**팀 주요 기능**
- Servlet + JSP 기반 전통적인 MVC 웹 계층 설계
- 세션 기반 로그인, 학습 팁/질문 공유 커뮤니티(게시판)

**💡 나의 기여**

| 역할 | 내용 |
|------|------|
| 스케줄러 CRUD | 날짜·시간대별 학습 계획 등록/조회/수정/삭제 비즈니스 로직 및 DAO 설계 |
| UI 뷰 설계 | JSP 기반 리스트형·달력형 뷰 구현 및 데이터 연동 |
| 요청 흐름 제어 | Servlet을 통한 클라이언트 요청 처리 및 DB 통신 흐름 제어 |

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
