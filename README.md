## 📍 프로젝트명: SCHOLLI

<img src="https://github.com/judymoody59/Musccat_Example/assets/108432112/b8bf2704-748e-4b22-9140-5c4692dd2db9" width="250" height="250" />
<br>
<br>


## 📒 프로젝트 설명
분산된 장학금 정보를 통합하여 머신러닝을 통해 사용자 프로필에 맞는 장학금을 추천하고, 생성형 ai를 통해 지원서 작성 팁 제공 및 지원서를 자동으로 작성해주는 서비스

<br>

## 📑 기능
- 통합된 데이터 : 다양한 기관과 단체의 장학금 정보를 통합하여 하나의 데이터 베이스로 관리

- 맞춤형 추천 시스템 : 사용자의 프로필을 분석하여 개인에게 최적화된 장학금을 추천

- 지원서 작성 팁 제공 : AI 기술을 활용하여 이전 수혜자들의 조언 및 팁을 추출하여 제공

- AI 기반 지원서 작성 : 생성형 AI 기술을 활용하여 사용자가 지정한 작성 방향을 바탕으로 지원서를 작성

<br>

## 👩‍💻 팀원

<table border="1" cellspacing="0" cellpadding="0" width="90%">
    <tr width="100%">
        <td width="10%" align="center"><a href= "https://github.com/SeoYeomm">이서연</a></td>
        <td width="10%" align="center"><a href= "https://github.com/hayong39">변하영</a></td>
        <td width="10%" align="center"><a href= "https://github.com/judymoody59" width="100px">채민주</a></td>
    </tr>
    <tr width="100%">
        <td width="10%" align="center"><img src = "https://avatars.githubusercontent.com/SeoYeomm"></td>
        <td width="10%" align="center"><img src = "https://avatars.githubusercontent.com/hayong39"/></td>
        <td width="10%" align="center"><img src = "https://avatars.githubusercontent.com/judymoody59"/></td>
    </tr>
    <tr width="100%">
        <td width="10%" align="center">AI & BE</td>
        <td width="10%" align="center">AI & BE</td>
        <td width="10%" align="center">FE</td>
   </tr>
</table>

<br>

## 🗃️ 개발 레포지토리

#### 백엔드
  - [Musccat_Project_BE](https://github.com/Musccat/Musccat_Project_BE)
#### 프론트엔드
  - [Musccat_Project_FE](https://github.com/Musccat/Musccat_Project_FE)

<br>


## 🛠️ 기술 스택

#### AI 
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=TensorFlow&logoColor=white"> <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=PyTorch&logoColor=white"> 

#### 백엔드
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white"> <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=Django&logoColor=white"> <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white"> <img src="https://img.shields.io/badge/Amazon RDS-527FFF?style=for-the-badge&logo=Amazon RDS&logoColor=white"> <img src="https://img.shields.io/badge/Amazon EC2-FF9900?style=for-the-badge&logo=Amazon EC2&logoColor=white"> <img src="https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=Selenium&logoColor=white">

#### 프론트엔드
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=HTML5&logoColor=white"> <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=CSS3&logoColor=white"> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=black"> <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=black"> <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=Figma&logoColor=white"> 

#### 협업
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white">

<br>

## ⚙️ 개발환경 설정

#### 백엔드 실행 터미널

프로젝트에 필요한 패키지들이 다른 프로젝트와 격리되도록 가상 환경을 설정한다.  
```
python -m venv "이름" #가상 환경 시작
```
<br>

가상환경을 생성했다면 활성화하여 해당 환경 내에서 작업할 수 있도록 이동한다.

```
source "이름"/Scripts/activate #가상 환경으로 이동
```

<br>

가상 환경이 활성화된 상태에서 Django 프로젝트를 생성한다.

```
django-admin startproject "프로젝트 이름" #프로젝트 시작
```

<br>

Django 프로젝트 내에서 실제로 기능을 구현하는 단위인 앱을 생성한다.

```
python manage.py startapp "앱 이름" #앱 시작
```

<br>

모든 설정이 완료되면 Django 개발 서버를 실행한다.

```
python manage.py runserver #서버 시작 
```

#### 프론트엔드 실행 터미널

create-react-app(CRA)를 이용하기 위해선 Node.js 와 npm 설치가 되어있어야 한다.

- npm(node package manager) v6. 14.0 이상
- Node.js (JavaScript runtime) 14.0.0 이상

설치가 모두 완료되었다면 npx 명령어를 통해 CRA를 실행할 수 있다.
```
npx create-react-app <프로젝트 이름> // React 웹 애플리케이션 프로그램 생성
npm start // 애플리케이션 실행
```
