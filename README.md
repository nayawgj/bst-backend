# BST Backend

**Personal project — REST API for the Book Discussion Platform “Booksaeteum” (북새틈).**

Spring Boot backend providing API services for Booksaeteum, an online book-discussion platform. 
Built as a capstone project in Ewha to learn backend architecture, deployment, and integration with a separate frontend repository.

---

## 🚀 Quick Start
```bash
# Clone repository
git clone https://github.com/nayawgj/bst-backend.git
cd bst-backend

# Run (Gradle)
./gradlew bootRun

# Or build and run jar
./gradlew clean bootJar
java -jar build/libs/*.jar
```

### Environment Example
```env
SPRING_DATASOURCE_URL=jdbc:mysql://localhost:3306/booksaeteum
SPRING_DATASOURCE_USERNAME=root
SPRING_DATASOURCE_PASSWORD=example
JWT_SECRET=your_secret_key
```

> Keep secrets out of Git. Use `.env` or `application-local.yml` locally.

---

## 🧩 Tech Stack
- **Language:** Java (Spring Boot)
- **Database:** MySQL
- **Build Tool:** Gradle
- **Infra (optional):** Docker, AWS RDS

---

## 📌 Notes
- Designed for learning and demonstration — not production-ready.
- Used together with the [BST Frontend (React)](https://github.com/nayawgj/bst-frontend).

---

## 🇰🇷 한국어 버전

**개인 프로젝트 — 졸업프로젝트 ‘북새틈(Booksaeteum)’의 백엔드 REST API 서버입니다.**

"북새틈"은 책에 대해 토론을 나누고, 독후감을 작성하여 공유할 수 있는 온라인 독서 커뮤니티입니다.
Spring Boot 기반으로 사용자 인증, 도서 관리, 게시판 등의 기능을 제공합니다. 
별도의 프론트엔드 레포지토리와 연동되며, 백엔드 구조 및 배포 환경 학습을 목적으로 제작되었습니다.

### 🚀 빠른 시작
```bash
git clone https://github.com/nayawgj/bst-backend.git
cd bst-backend
./gradlew bootRun
```

### 환경 변수 예시
```env
SPRING_DATASOURCE_URL=jdbc:mysql://localhost:3306/booksaeteum
SPRING_DATASOURCE_USERNAME=root
SPRING_DATASOURCE_PASSWORD=example
JWT_SECRET=your_secret_key
```

> 민감정보는 `.env` 또는 `application-local.yml`을 사용하시길 바랍니다.

### 🧩 기술 스택
- Java / Spring Boot
- MySQL
- Gradle
- (선택) Docker, AWS RDS

### 📌 참고
- 학습 및 시연용 프로젝트로, 운영 환경용이 아닙니다.
- 프론트엔드 레포지토리: [BST Frontend (React)](https://github.com/nayawgj/bst-frontend)

<img width="415" height="860" alt="image" src="https://github.com/user-attachments/assets/61b76a19-4277-4e13-923a-61ee34c5c5a6" />
