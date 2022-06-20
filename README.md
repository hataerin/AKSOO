# 🤝🏻악수

![image](https://user-images.githubusercontent.com/26705587/174594414-eb339f69-f3e0-430f-901f-2cf0aba95377.png)



## 📌프로젝트 소개

악수는 **게임형 지문자 학습 서비스**입니다.

- 후천적 청각장애로 인해 수화를 배워야하지만 수화가 어려워 지문자를 먼저 배워야 하는 사람
- 지문자를 배우고 싶은데 단순히 배우는 것에 싫증이 나서 색다른 방법으로 배우고 싶은 사람
- 게임에서 선의의 경쟁을 통해 1위를 해보고 싶은 사람

악수는 **지문자를 쉽고, 재밌게 배우고싶은 모든 분들**을 위해 만들어졌습니다.

<br><br>

## 📺 시연영상

> 사진을 클릭하면 유튜브 페이지로 이동합니다

<p align='middle'><a href="https://www.youtube.com/watch?v=qbOyOyLsYps" target="_blank"><img src="https://user-images.githubusercontent.com/26705587/174591455-754f48ae-32dc-423e-9b6e-55907de5d3a4.JPG" width="600px"/></a></p>

<br><br>

## ⚙ 기술 스택

### 💻Back-End

#### 프레임워크

- Django - 3.2.5
- djangorestframework(DRF) - 3.12.4

#### 라이브러리

- djangorestframework-simplejwt - 4.8.0
- dj-rest-auth - 2.1.11
- PyMySql - 1.0.2
- 이외의 자세한 라이브러리는 [requirements.txt](./Back/django-game/requirements.txt) 참조

</br>

### ✨Front-End

#### 프레임워크

- Vue.js - 2.6.14

#### 라이브러리

- axios - 0.21.1
- vuex - 3.6.2
- vue-router - 3.5.2
- 이외의 자세한 라이브러리는 [package.json](./Front/client/package.json) 참조

</br>

### 👾 Machine Learning

#### 프레임워크

- TensorFlow.js - 3.9.0

#### 라이브러리(모델)

- [fingerpose](https://github.com/andypotato/fingerpose#readme) - 0.0.2
- [tensorflow-models/handpose](https://github.com/tensorflow/tfjs-models#readme) - 0.0.7

<br><br>

## 🔨  설치 및 실행방법

#### 폴더구조

```
📁 Front				# 프론트 
📁 Back					# 백엔드 
📁 AI					# 인공지능
```

</br>

#### 프로젝트 실행방법(Local 기준)

> 각 폴더 별로 실행 시켜야 합니다.

##### ✔Back-End

###### 1) Back/django-game/ 으로 이동한다.

###### 2) 터미널창을 열어 다음과 같이 입력하여 가상환경을 만든다.

```bash
python -m venv venv
```

###### 3) 다음과 같이 입력하여 가상환경을 킨다.

```bash
source venv/Scripts/activate
```

###### 4) (처음 실행시에만) 다음과 같이 입력하여 필요한 package를 현재 가상환경에서 설치한다.

```bash
pip install -r requirements.txt
```

###### 5) Django 서버를 킨다.

```bash
python manage.py runserver
```

</br>

##### ✔Front-end

###### 1) .env.local 파일을 Front/client/ 경로에 만든다.

###### 2) .env.local을 열어 아래 내용을 붙여넣는다.(기본으로 켜질 로컬호스트 주소)

```
VUE_APP_SERVER_URL = http://127.0.0.1:8000
```

###### 3) Front/client/ 경로에서 터미널창을 킨다.

###### 4) (처음 실행시에만) 다음과 같이 package를 설치한다.

```bash
npm install
```

###### 5) 다음과 같이 클라이언트를 로컬 환경에서 실행한다.

```bash
npm run serve
```

</br>



## 🚩주요기능

1. **메인페이지**

   <img src="https://user-images.githubusercontent.com/26705587/174593133-67e871b2-75c6-4479-b98b-389dccf9a0cf.JPG" height="300px"/>

   <br>

2. **학습하기**

   <img src="https://user-images.githubusercontent.com/26705587/174593152-f8b7130d-9c9b-42f2-a16a-4e8c47fb41ba.JPG" height="300px"/>

   <br>

3. **산성비 게임**

   <img src="https://user-images.githubusercontent.com/26705587/174593231-5a15204a-8019-484a-bdfa-f6126a371d66.JPG" height="300px"/>

   <br>

4. **단어맞추기 게임** 

   <img src="https://user-images.githubusercontent.com/26705587/174593213-60013f02-6a20-4fa2-985f-749a77bdb196.JPG" height="300px"/>

   <br>

5. **카드뒤집기 게임**

   <img src="https://user-images.githubusercontent.com/26705587/174593260-4f0f3f7a-5fee-470d-b5e9-3798c11ac445.JPG" height="300px"/>

   <br>

6. **명예의 전당**

   <img src="https://user-images.githubusercontent.com/26705587/174593303-119f341e-b894-43f4-8c68-3af8d6f62c3a.JPG" height="300px"/>

   <br>

7. **마이페이지**

   <img src="https://user-images.githubusercontent.com/26705587/174593291-4a39611e-022b-408f-b103-ecda9738baf3.JPG" height="300px"/>

   <br><br><br>



## 📚WIKI

👉[B306팀의 협업방법 보러가기](https://github.com/hataerin/AKSOO/wiki)👈

👉[프로젝트 소개](./악수_소개.pdf)👈

