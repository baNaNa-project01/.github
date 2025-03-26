# **🍌 배나낭: 국내 여행자들을 위한 통합 커뮤니티 플랫폼**  

<br>

> **"국내 여행 정보를 한곳에서! AI 기반 맞춤 추천과 커뮤니티로 더욱 편리한 여행을 즐기세요."**  

<br/>

![랜딩 페이지 0](./랜딩%20페이지-0.svg)
![랜딩 페이지 0](./엘리베이터%20피칭-2.svg)
![랜딩 페이지 0](./엘리베이터%20피칭-3.svg)
![랜딩 페이지 1](./랜딩%20페이지-1.svg)
![랜딩 페이지 2](./랜딩%20페이지-2.svg)
![랜딩 페이지 3](./랜딩%20페이지-3.svg)
![랜딩 페이지 4](./랜딩%20페이지-4.svg)
![랜딩 페이지 5](./랜딩%20페이지-5.svg)
![랜딩 페이지 6](./랜딩%20페이지-6.svg)
![랜딩 페이지 7](./랜딩%20페이지-7.svg)

<br/>

## **👥 Team Members (팀원 소개)**  

| 역할 | 이름 |
|:------:|:------:|
| **PM (Project Manager)** | 여채현 |
| **Design** | 여채현 |
| **Web Development** | 여채현, 은나현 |
| **Server Development** | 송창욱, 은나현, 이태훈, 장정명 |

<br>

## 🚀 **배포 링크**
🔗 **[배나낭 웹사이트 바로가기](https://banana-project01.github.io/baNaNa-frontend/)**

<br>

# **0. Getting Started (시작하기)**  
배나낭 프로젝트를 로컬에서 실행하려면 아래 단계를 따라 주세요.  

```bash
# 프로젝트 클론
git clone https://github.com/your-repository.git

# 프로젝트 폴더로 이동
cd your-repository

# 패키지 설치
npm install

# 로컬 서버 실행
npm start
```

💡 **로컬 서버 실행 후** `http://localhost:3000` 에서 확인 가능합니다.  

<br>

# **1. Project Overview (프로젝트 개요)**  
### ✨ **배나낭이란?**  
**배나낭**은 국내 여행자들을 위한 **여행 정보 통합 플랫폼**입니다.  
사용자는 **관광지 정보, 맛집 추천, AI 기반 맞춤 여행 일정, 커뮤니티 소통** 등을 한곳에서 이용할 수 있습니다.  

### **📌 주요 기능**  
- **AI 여행 추천** – 원하는 조건을 입력하면 AI가 맞춤형 여행 루트를 추천  
- **관광지 정보 탐색** – 지도에서 지역별 여행지 & 맛집 정보 확인  
- **맛집 이상형 월드컵** – 게이미피케이션 요소를 활용한 맛집 선택  
- **커뮤니티 기능** – 여행 후기, 추천 장소 공유, 댓글 기능  
- **소셜 로그인 지원** – 카카오, 네이버, 구글 OAuth 연동  

---
<br>

# **2. Key Features (주요 기능)**  

### ✅ **1) AI 여행 추천**  
- 사용자의 **지역, 기간, 동행인, 테마, 일정 스타일**을 바탕으로 AI가 최적의 여행 루트를 생성  
- 추천된 경로는 **지도에 마커로 표시되며 Day1, Day2 일정까지 자동 생성**  
- **🚧 현재 개발 중 (Coming Soon!)**  

### ✅ **2) 지역별 관광지 & 맛집 정보**  
- **TourAPI + Kakao Maps API 연동**  
- 지도에서 **관광지, 맛집, 숙소 정보를 마커로 표시**  
- 검색 및 필터 기능 지원  

### ✅ **3) 맛집 이상형 월드컵**  
- 여행지에서 무엇을 먹을지 고민될 때, **게이미피케이션을 활용한 선택 기능 제공**  
- **월드컵 결과 TOP3**를 메인에서 한눈에 확인 가능  
- **🚧 현재 개발 중 (Coming Soon!)**  

### ✅ **4) 커뮤니티 기능**  
- 여행 후기, 맛집 추천, 꿀팁 등을 자유롭게 공유  
- 게시글 CRUD(작성, 수정, 삭제, 조회), 댓글 기능 지원  
- **🚧 현재 개발 중 (Coming Soon!)**  

---
<br>

# **3. Technology Stack (기술 스택)**

## 🖥 **Frontend**

| 기술 | 배지 |
|------|------|
| HTML5 | ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) |
| CSS3 | ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white) |
| Vanilla JS | ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) |
| Bootstrap | ![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white) |

<br>

## 🔧 **Backend**

| 기술 | 배지 |
|------|------|
| Flask | ![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white) |
| Node.js | ![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white) |
| Express.js | ![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white) |
| Supabase | ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white) |
| Google Gemini API | ![Gemini](https://img.shields.io/badge/Google%20Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white) |
| TourAPI | ![TourAPI](https://img.shields.io/badge/TourAPI-FF5A5F?style=for-the-badge&logo=datadog&logoColor=white) |
| Kakao Maps API | ![Kakao](https://img.shields.io/badge/Kakao%20Maps-FFCD00?style=for-the-badge&logo=kakao&logoColor=000000) |

<br>

## 🚀 **DevOps**

| 기술 | 배지 |
|------|------|
| Glitch | ![Glitch](https://img.shields.io/badge/Glitch-9333EA?style=for-the-badge&logo=glitch&logoColor=white) |
| Render | ![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=black) |
| GitHub Pages | ![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-121013?style=for-the-badge&logo=github&logoColor=white) |
