
# 🧑‍💼 EMS (Employee Management System)

**EMS (Employee Management System)**는 직원 정보를 효율적으로 관리할 수 있는 웹 애플리케이션입니다.  
프론트엔드와 백엔드를 분리하여 개발하였으며, Angular와 Spring Boot를 기반으로 하고, MySQL 데이터베이스와 연동되어 있습니다.

🔗 GitHub Links
- [EMS-Frontend](https://github.com/JihyeKim39/EMS-Frontend)  
- [EMS-Backend](https://github.com/JihyeKim39/EMS-Backend)

## 🔧 기술 스택

### Frontend (Angular)
- Angular 17
- TypeScript
- RxJS
- SCSS

### Backend (Spring Boot)
- Java 17
- Spring Boot 3
- Spring Data JPA
- Spring Web
- MySQL

## ✨ 주요 기능

- 직원 목록 조회
- 직원 상세 보기
- 직원 등록, 수정, 삭제
- RESTful API 기반 데이터 통신
- 직관적인 UI 구성

## ⚙️ 설치 및 실행 방법

### Backend 실행

```bash
# 레포 클론
git clone https://github.com/JihyeKim39/EMS-Backend.git
cd EMS-Backend

# application.properties 설정
# (MySQL 연결 정보 예시)
spring.datasource.url=jdbc:mysql://localhost:3306/ems_db
spring.datasource.username=root
spring.datasource.password=비밀번호

# Gradle 빌드 및 실행
./gradlew bootRun
```

> 백엔드는 기본적으로 `localhost:8080` 에서 실행됩니다.

### Frontend 실행

```bash
# 레포 클론
git clone https://github.com/JihyeKim39/EMS-Frontend.git
cd EMS-Frontend

# 의존성 설치
npm install

# 개발 서버 실행
ng serve
```

> 프론트는 기본적으로 `localhost:4200` 에서 실행되며, 백엔드 API와 통신합니다.

## 💡 향후 개선 예정

- 로그인 및 권한 관리 기능 추가
- 반응형 UI 개선
- 테스트 코드 작성
- AWS 등 클라우드 환경으로 배포

## 🙋‍♀️ 개발자

- Jihye Kim  
  [GitHub](https://github.com/JihyeKim39)
