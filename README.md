<img width=70% src="https://github.com/user-attachments/assets/35cd3f17-12f0-4daa-a9aa-ea3cafa912f7">

# OpenAPI를 활용한 식품영양정보 조회 서비스

### 📖 프로젝트 개요
건강 및 웰빙에 대한 관심이 증가함에 따라 제로 음료, 저칼로리 식품 등의 영양 성분을 확인하는 소비자가 증가하여 사용자가 식품의 영양 성분을 손쉽게 확인하면 좋겠다는 생각에 계획
<br/><br/>

### 🚀 프로젝트 목표
- 식약처의 식품 영양성분(DB) OpenAPI를 활용하여 식품 영양성분 정보 사용
- API 통신을 통해 가져온 데이터를 프론트에서 보여주도록 설계
<br/><br/><br/>

## 📝 프로젝트 설명

### 💼 기능
- 사용자가 입력한 식품명에 맞는 영양성분 정보를 제공
<br/><br/>

### 🗺 기술 설계도
<img width=100% src="https://github.com/hkyuuu00/dev-mode/assets/155419559/b46445cc-97ab-4af1-a1a9-07443e14f6c6"><br/><br/>


### 💻 기술 스택
- **OS:** &nbsp;&nbsp;![Windows 11](https://img.shields.io/badge/Windows%2011-%230079d5.svg?style=for-the-badge&logo=Windows%2011&logoColor=white) ![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
- **Container 배포:** &nbsp;&nbsp;![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
- **FrameWork:** &nbsp;&nbsp;![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB ) ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
- **Style:** &nbsp;&nbsp;![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
- **Language:** &nbsp;&nbsp;![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
- **Tools:** &nbsp;&nbsp;![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
<br/><br/>


### ✨ 주요 기능 및 이미지
📌 Home<br/>
<img width=100% src="https://github.com/hkyuuu00/dev-mode/assets/155419559/4899a646-3abc-4837-927d-1002c53329a8"><br/><br/>
- **메뉴바:** 로고와 각종 기능들을 이용할 수 있는 메뉴 바 구현<br/>
- **광고:** 사용자에게 어떻게 사용하는지와 사용하고 싶도록 디자인 구현<br/><br/><br/>

📌 Account<br/>
<img width=100% src="https://github.com/hkyuuu00/dev-mode/assets/155419559/2da2bd54-a770-4bd0-a697-6817690276a2"><br/><br/>
- **회원가입:** ID를 입력하여 회원가입을 진행, 회원가입 시 5000포인트를 적립되며 중복 ID 불가<br/>
- **추천인 등록:** 추천인을 등록할 수 있으며 추천을 한 사람에게는 500포인트, 받은 사람에게는 1000포인트를 적립, 추천은 계정 당 1회만 가능<br/>
- **회원탈퇴:** ID를 입력하여 회원탈퇴를 진행, 회원탈퇴 시 적립 포인트 모두 삭제<br/><br/><br/>

📌 Payment<br/>
<img width=100% src="https://github.com/hkyuuu00/dev-mode/assets/155419559/244033d6-f968-43ae-af4b-cff67ab39ffd"><br/><br/>
- **결제:** 본인의 ID를 입력하고 결제할 가격과 사용할 포인트 입력 (사용하지 않을 시에는 0 입력)<br/>
- **포인트 적립:** 사용자가 결제 진행 후 결제한 가격의 1% 포인트 적립<br/>
- **관리자 수수료:** 결제한 가격의 2% 수수료를 징수<br/><br/><br/>

📌 Send<br/>
<img width=100% src="https://github.com/hkyuuu00/dev-mode/assets/155419559/fe2fd520-fee9-4f44-8473-cdeac31fc851"><br/><br/>
- **포인트 선물:** 보내는 유저와 받는 유저의 ID를 입력 후 선물 포인트 입력 후 버튼을 누르면 5% 수수료를 빼고 받는 유저에게 지급<br/>
- **관리자 수수료:** 선물 포인트의 5% 수수료를 징수<br/><br/><br/>

📌 Event<br/>
<img width=100% src="https://github.com/hkyuuu00/dev-mode/assets/155419559/a1237384-a054-4589-a2ba-5a715ca32427"><br/><br/>
- **로또 참여:** 유저 ID를 입력하여 참여, 입력한 유저는 100포인트를 차감하고 Lotto 총 금액에 추가, 로또 당첨 시 Lotto 총 금액에 대한 포인트를 받음<br/>
- **회원정보 및 Lotto 금액:** 유저들이 서비스를 이용하면서 자신의 포인트와 로또 금액을 볼 수 있도록 구현<br/><br/><br/>

📌 Admin<br/>
<img width=100% src="https://github.com/hkyuuu00/dev-mode/assets/155419559/074ea8f0-270b-4e14-a45d-021895b1e2b0"><br/><br/>
- **비밀번호 입력:** 관리자 페이지이기에 다른 유저가 들어오지 못하도록 패스워드 입력 후 접근 가능<br/>
- **수수료 조회:** 관리자가 징수한 수수료를 확인할 수 있도록 구현<br/>
- **로또 이벤트 참여자 조회:** 로또의 참여자 명단을 기록하도록 구현<br/>
- **로또 추첨 버튼:** 로또를 추첨하여 당첨된 유저에게 Lotto 총 금액에 모인 포인트 지급, 로또는 랜덤으로 당첨<br/><br/><br/><br/><br/>

### 🎧 <a href="https://youtu.be/RS7BLJ2unoM](https://youtu.be/yycpVzCdrRU">시연영상</a>
</br></br></br></br>

### 🛠 문제 해결 과정
⚠️ API 통신 에러<br/>
<table>
  <tr>
    <td>
    <strong>문제</strong>
    </td>
    <td>
    <strong>API 통신을 하는 과정에서 에러 발생</strong>  
    </td>
  </tr>
  <tr>
    <td>원인</td>
    <td>동일한 출처의 리소스에만 접근하도록 제한</td>
  </tr>
  <tr>
    <td>해결</td>
    <td>한 도메인 웹 페이지가 다른 도메인 을 가진 리소스에 액세스 할 수 있도록 CORS 사용</td>
  </tr>
</table><br/><br/>

⚠️ 체인코드에서 사용자 정보 조회<br/>
<table>
  <tr>
    <td>
    <strong>문제</strong>
    </td>
    <td>
    <strong>사용자 정보를 전체 불러오는 것에 어려움</strong>  
    </td>
  </tr>
  <tr>
    <td>원인</td>
    <td>처음에는 입력값을 받아 해당 데이터를 조회하는 방식을 가지고 수정</td>
  </tr>
  <tr>
    <td>해결</td>
    <td>해당 데이터를 모두 받아 Json으로 파싱 후 Key, Value 값을 호출하여 출력</td>
  </tr>
</table><br/><br/><br/><br/>

## ⚙️ 프로젝트 설치 및 실행 방법

### 📝 Prerequisites
- Oracle VM VirtualBox 6.1
- Ubuntu 22.04.x
- cURL
- Docker Community Edition CE 23.0.6
- Docker Compose 1.27.4 이상
- Go 1.16.7
- Git 2.9.x 이상
- Python 2.7.17
- Node.js 12.13.1
- npm 5.6.0
- VSCode v1.28

