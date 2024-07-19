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
<img width=100% src="https://github.com/user-attachments/assets/8cfa2b59-460f-46d2-9196-fbf5fd0e59ad"><br/><br/>


### 💻 기술 스택
- **OS:** &nbsp;&nbsp;![Windows 11](https://img.shields.io/badge/Windows%2011-%230079d5.svg?style=for-the-badge&logo=Windows%2011&logoColor=white) ![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
- **Container 배포:** &nbsp;&nbsp;![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
- **FrameWork:** &nbsp;&nbsp;![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB ) ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
- **Style:** &nbsp;&nbsp;![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
- **Language:** &nbsp;&nbsp;![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
- **Tools:** &nbsp;&nbsp;![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
<br/><br/>


### ✨ 주요 기능 및 이미지
📌 메인화면<br/>
<img width=100% src="https://github.com/user-attachments/assets/7ded6ebb-6673-49b1-9d00-b2340787ca90">
- 검색창: 사용자가 식품명을 입력하면 해당 식품의 영양성분정보를 제공<br/><br/><br/>
<img width=100% src="https://github.com/user-attachments/assets/da497b53-605d-4dcc-aebb-57f5b7ad390c">
- 식품영양정보 제공: 1회 제공량, 열량, 탄수화물, 단백질, 지방, 당류, 나트륨의 정보를 제공<br/><br/><br/>
<img width=100% src="https://github.com/user-attachments/assets/ab140aad-fee8-48d4-8e1b-4ec380cbb2d4">
- 페이지 분류: 검색결과가 20개 이상일 경우 나누어 확인할 수 있도록 페이지네이션 기능 구현<br/><br/><br/>
<img width=100% src="https://github.com/user-attachments/assets/4f78400b-5776-434d-bf6c-078ebed87803">
- 좋은 가시성: 같은 식품명의 상품이 존재하는 경우를 대비하여 가시성을 높이기 위한 UI 구현<br/><br/><br/>



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
    <td>검색 키워드의 URL 인코딩 과정에서의 에러 및 API 서버에러</td>
  </tr>
  <tr>
    <td>해결</td>
    <td>Try-catch문을 사용하여 데이터처리 에러로 구분하고 예외처리 및 에러 표시</td>
  </tr>
</table><br/><br/>

