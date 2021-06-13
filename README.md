# 실시간 퀴즈 - 관리자 페이지 (Real Time Quiz - Admin Page)

## 👉 프로젝트 소개
관리자 페이지로 유저페이지를 컨트롤 하여 실시간으로 퀴즈를 풀 수 있는 프로젝트입니다.

'realtime-quiz-admin'은 실시간 퀴즈가 진행 될 때 user들의 입장, 퀴즈 진행상황을 컨트롤하고 통계를 확인을 할 수 있는 관리자 페이지에 대한 코드입니다.

---

## 📆 프로젝트 기간

- 2021.5.17 ~ 2021.6.2

---

## 👥 프로젝트 인원
Frontend
  - Admin Page: 김효진
  - User Page: 박성은

Backend
  - 안정현 (Python) - 연결
  - 정재유 (Node.js)

----

## ⚛️ 기술 스택
- Frontend
  - React.js
  - Recoil
  - Scss
  - WebSocket API
  - Chart.js
  - canvasJS
  - Git
- Backend 
  - Python
  - PostgreSQL
  - Django
  - Node.js

---

## ⚙️ 협업 도구
- Notion: API document 사용
- Google Sheets: 주간 계획 및 진행상황, FlowChart 공유
- Zeplin: 디자이너와 소통
- Telegram

---

## 👩🏻‍💻 구현 내용 (admin page)
- WebSocket 통신으로 User page에 quizNumber, status(퀴즈 진행상태) state 전송
- 'status'조건에 따라 컴포넌트를 보여주어 하나의 url(한 페이지 내)에서 퀴즈 컨트롤
- Recoil 상태관리 라이브러리를 활용한 menu tab, status, quizNumber 등 상태관리
- Menu Tab 구현으로 퀴즈 진행과 동시에 업데이트된 data 집계 확인이 가능하도록 설정
  (tab 1: 데이터 집계, tab 2 :퀴즈 컨트롤)
- Chart.js와 canvasJS 라이브러리를 이용한 유저 데이터와 퀴즈 데이터 집계
- JWT와 로컬스토리지를 사용하여 관리자 페이지 로그인, 로그아웃 구현

--- 
## 💻 구현 영상
youtube.com/watch?v=M2E9qwIMJe8
