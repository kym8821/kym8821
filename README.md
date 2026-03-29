<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=wave&color=auto&height=300&section=header&text=kym8821&fontSize=90" />
</div>

<br/><br/>

<div align="center">
  <h1>👋 Backend Developer 김용민입니다</h1>
</div>
  
문제를 단순히 해결하는 것이 아니라, **원인을 구조적으로 분석하고 재발하지 않는 방식으로 개선하는 백엔드 개발자**입니다.

서비스 개발 과정에서 발생하는 성능 문제와 구조적 한계를 해결하는 데 집중해왔습니다. 
JPA N+1 문제를 분석하고 조회 전략을 재구성하여 **API 응답 속도를 약 40% 개선**했고, 실시간 스트리밍 시스템에서는 I/O 구조와 전송 방식을 개선하여 **FPS 5 → 30, 메모리 사용량 안정화(700MB 수준)** 를 달성했습니다.

또한 Redis, Kafka, WebSocket 기반의 실시간 파이프라인을 설계하며 **DB Write 횟수를 45회 → 1회로 줄이는 구조 개선**을 경험했고, MSA 구조를 직접 적용하며 **아키텍처 선택의 트레이드오프**를 고민해왔습니다

기술은 목적이 아니라 문제 해결을 위한 도구라고 생각합니다. 항상 “왜 이 구조가 필요한가”를 고민하며, **현재 상황에 가장 적합한 설계를 선택하는 개발자**가 되고자 합니다.

  <!-- <img src="https://github-readme-stats.vercel.app/api?username=kym8821&show_icons=true&theme=radical" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=kym8821&layout=compact" />   -->
</div> 

<br/><br/>

<div align="center">
  <h1>📚 STACKS</h1>
</div>

<div align="center">
  <img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"> 
  <img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white"> 
  <img src="https://img.shields.io/badge/kotlin-7F52B1?style=for-the-badge&logo=kotlin&logoColor=white"> 
  <img src="https://img.shields.io/badge/django-green?style=for-the-badge&logo=django&logoColor=white"> 
  <img src="https://img.shields.io/badge/express-000000?style=for-the-badge&logo=express&logoColor=white"> 
  <img src="https://img.shields.io/badge/docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
  <img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black">
  <img src="https://img.shields.io/badge/mysql-000000?style=for-the-badge&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/jpa-000000?style=for-the-badge&logo=jpa&logoColor=white">
</div>

<br/><br/>

<div align="center">
  <h1>🚀 PROJECTS</h1>
</div>

### 🎨 카카오톡 테마 커스터마이징 서비스  
> 사용자가 직접 테마를 제작하고 공유할 수 있는 커스터마이징 플랫폼

**📌 개요**
- 이미지 및 스타일 요소를 조합하여 카카오톡 테마를 생성하고 공유할 수 있는 서비스

**⚙️ 기술 스택**
- **Backend**: Java, Spring Boot, Spring Data JPA, MySQL, Docker, Redis  
- **Frontend**: React, TypeScript  

**👨‍💻 주요 기여**
- 테마 및 게시글 API 설계 및 구현
- 조회 성능 최적화 (**쿼리 14 → 7, 응답시간 40% 개선**)
- Docker 멀티 스테이징 적용 (**500MB → 150MB 이미지 최적화**)
- 안드로이드 환경 테마 생성 및 적용 기능 구현

**🔗 Repository**
- Frontend: https://github.com/kakao-theme-maker/Web-frontend  
- Backend: https://github.com/kakao-theme-maker/backend  

---

### 🥁 AI 기반 실시간 드럼 연주 채점 서비스  
> 실시간 연주 데이터를 분석하여 정확도를 평가하는 AI 기반 음악 서비스

**📌 개요**
- 사용자 드럼 연주를 실시간 분석하여 박자 및 음 정확도 측정
- 업로드된 악보를 분석하여 서비스에서 활용 가능한 포맷으로 변환

**⚙️ 기술 스택**
- **Backend**: Java, Spring Boot, Spring Cloud, JPA, WebSocket(STOMP), MySQL, Docker, Kafka, Redis  
- **Frontend**: Flutter, Dart  

**👨‍💻 주요 기여**
- JWT 기반 인증/인가 시스템 구축
- STOMP 기반 실시간 데이터 처리 파이프라인 설계
- Spring Cloud 기반 MSA 아키텍처 구축
- Docker 이미지 최적화 (**2GB → 700MB**)

**🔗 Repository**
- https://github.com/kookmin-sw/capstone-2025-22  

---

### 🤝 자립 준비 청년을 위한 실시간 매칭 시스템  
> 멘토-멘티를 실시간으로 연결하고 소통을 지원하는 플랫폼

**📌 개요**
- 자립 준비 청년을 위한 멘토링 매칭 및 정보 제공 서비스

**⚙️ 기술 스택**
- **Backend**: Kotlin, Spring Boot, JPA, WebSocket(STOMP), MySQL, Docker  
- **Frontend**: React, JavaScript  

**👨‍💻 주요 기여**
- JWT 기반 인증/인가 구현
- STOMP 기반 실시간 채팅 시스템 구현
- 채팅방 및 메시지 관리 API 설계 및 개발

**🔗 Repository**
- Frontend: https://github.com/cooing-kmu/cooing-frontend  
- Backend: https://github.com/cooing-kmu/cooing-backend  

---

### 🏆 백준 주간 랭킹 서비스  
> solved.ac 기반 문제 추천 및 사용자 랭킹 서비스

**📌 개요**
- solved.ac API를 활용한 문제 추천 및 주간 랭킹 제공

**⚙️ 기술 스택**
- **Backend**: TypeScript, Express, MySQL  
- **Frontend**: React, TypeScript  

**👨‍💻 주요 기여**
- 주간 랭킹 시스템 구현
- 문제 정보 크롤링 기능 개발
- 사용자 인증 기능 구현

**🔗 Repository**
- Frontend: https://github.com/code-kookmin/comin_ft  
- Backend: https://github.com/code-kookmin/comin_be  

---

### 🌧 실시간 강수량 기반 침수 예측 서비스  
> 실시간 데이터를 활용한 지역별 침수 위험도 분석 시스템

**📌 개요**
- 강수량 데이터를 기반으로 지역별 침수 위험도를 분석 및 제공

**⚙️ 기술 스택**
- **Backend**: Django, DRF, Python, MySQL  
- **Frontend**: React, JavaScript  

**👨‍💻 주요 기여**
- OpenStreetMap 기반 지도 격자 UI 구현 및 위험도 시각화
- 외부 강수량 API 연동 및 데이터 수집 파이프라인 구축
- 침수 위험도 산정 로직 설계 및 API 구현

**🔗 Repository**
- Frontend: https://github.com/K-PaaS-Competition/kPaas-fe  
- Backend: https://github.com/K-PaaS-Competition/KPaas-be

<!--
### **카카오톡 테마 커스터마이징 서비스**  
- 개요
  - 사용자가 카카오톡 테마를 직접 생성하고 공유할 수 있는 서비스  
  - 이미지 및 스타일 요소를 조합하여 테마를 제작하고 결과물을 공유할 수 있도록 지원  
- 기술
  - Backend : Java, Spring Boot, Spring Data JPA, MySQL, Docker, Redis
  - Frontend : React, TypeScript  
- 역할
  - Spring Boot 기반 테마 및 게시글 API 설계 및 구현
  - Spring Data JPA를 활용한 조회 로직 개선 및 성능 최적화 ( 쿼리 14 -> 7, 응답시간 40% 개선 )
  - Docker 멀티 스테이징을 적용하여 이미지 크기 개선 ( 500MB -> 150MB )
  - 안드로이드 환경에서 테마 생성 및 적용 기능 구현
- 리포지토리
  - Frontend : https://github.com/kakao-theme-maker/Web-frontend
  - Backend : https://github.com/kakao-theme-maker/backend
  
### **AI 기반 실시간 드럼 연주 채점 서비스**
- 개요
  - AI 모델 기반 사용자 드럼 연주를 실시간으로 분석하고, 박자/음의 정확도를 측정하는 서비스  
  - 사용자가 업로드한 드럼 악보를 분석하고, 서비스 내에서 활용할 수 있는 포멧으로 변환  
- 기술
  - Backend : Java, Spring Boot, Spring Cloud, Spring Data JPA, WebSocket, STOMP, MySQL, Docker, Kafka, Redis
  - Frontend : Flutter, Dart
- 역할
  - Spring Security 기반 JWT 인증/인가 기능 구현
  - STOMP 기반 실시간 드럼 연주 분석 파이프라인 구축 및 최적화
  - Spring Cloud 기반 MSA 환경 구축
  - 멀티 스테이지 빌드로 이미지 크기 개선 ( 2GB -> 700MB )
- 리포지토리
  - Frontend+Backend : https://github.com/kookmin-sw/capstone-2025-22

### **자립 준비 청년을 위한 실시간 매칭 시스템**
- 개요
  - 자립 준비 청년을 위한 실시간 멘토/멘티 매칭 서비스
  - 자립 시 필요한 정보를 수집 및 가공하여 사용자에게 제공
- 기술
  - Backend : Kotlin, Spring Boot, Spring Data JPA, WebSocket, STOMP, MySQL, Docker
  - Frontend : React, JavaScript
- 역할
  - Spring Security 기반 JWT 인증/인가 기능 구현
  - STOMP 기반 실시간 멘토/멘티 채팅 기능 구현
  - 채팅 및 채팅방 관리 API 구현
- 리포지토리
  - Frontend : https://github.com/cooing-kmu/cooing-frontend
  - Backend : https://github.com/cooing-kmu/cooing-backend

### **백준 주간 랭킹 서비스**  
- 개요
  - solved.ac API 기반 문제 추천 및 백준 주간 랭킹 서비스
- 기술
  - Backend : TypeScript, Express, MySQL
  - Frontend : React, TypeScript
- 역할
  - 주간 백준 랭킹 기능 구현
  - 문제 정보 크롤링 기능 구현
  - 사용자 인증 기능 구현
- 리포지토리
  - Frontend : https://github.com/code-kookmin/comin_ft
  - Backend : https://github.com/code-kookmin/comin_be

### **실시간 강수량 기반 지역별 침수 예측 서비스**  
- 개요
  - 실시간 강수량 데이터를 수집하여 지역별 침수 위험도를 제공하는 서비스
- 기술
  - Backend : Django, Django Rest Framework, Python, MySQL
  - Frontend : React, JavaScript
- 역할
  - OpenStreetMap 기반 지도 격자(Grid) UI를 구현하고, 침수 위험도에 따라 시각적으로 표현  
  - Django 및 외부 강수량 API를 연동하여 실시간 강수 데이터 수집 및 제공 시스템 구축  
  - 강수량 데이터를 기반으로 침수 위험도를 계산하고, 이를 제공하는 API 설계 및 구현  
- 리포지토리
  - Frontend : https://github.com/K-PaaS-Competition/kPaas-fe
  - Backend : https://github.com/K-PaaS-Competition/KPaas-be
-->

<br/><br/>

<div align="center">
  <h1>📘 STUDY LINKS</h1>
</div>

- [Spring Boot 블로그](https://kym8821.tistory.com/category/Spring)
- [Docker 블로그](https://kym8821.tistory.com/category/Docker)
- [기본개념 정리 블로그](https://kym8821.tistory.com/category/CS%20%EB%B0%8F%20%EA%B8%B0%EB%B3%B8%20%EA%B0%9C%EB%85%90)
