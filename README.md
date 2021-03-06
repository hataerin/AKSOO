# ๐ค๐ป์์

![image](https://user-images.githubusercontent.com/26705587/174594414-eb339f69-f3e0-430f-901f-2cf0aba95377.png)



## ๐ํ๋ก์ ํธ ์๊ฐ

์์๋ **๊ฒ์ํ ์ง๋ฌธ์ ํ์ต ์๋น์ค**์๋๋ค.

- ํ์ฒ์  ์ฒญ๊ฐ์ฅ์ ๋ก ์ธํด ์ํ๋ฅผ ๋ฐฐ์์ผํ์ง๋ง ์ํ๊ฐ ์ด๋ ค์ ์ง๋ฌธ์๋ฅผ ๋จผ์  ๋ฐฐ์์ผ ํ๋ ์ฌ๋
- ์ง๋ฌธ์๋ฅผ ๋ฐฐ์ฐ๊ณ  ์ถ์๋ฐ ๋จ์ํ ๋ฐฐ์ฐ๋ ๊ฒ์ ์ซ์ฆ์ด ๋์ ์๋ค๋ฅธ ๋ฐฉ๋ฒ์ผ๋ก ๋ฐฐ์ฐ๊ณ  ์ถ์ ์ฌ๋
- ๊ฒ์์์ ์ ์์ ๊ฒฝ์์ ํตํด 1์๋ฅผ ํด๋ณด๊ณ  ์ถ์ ์ฌ๋

์์๋ **์ง๋ฌธ์๋ฅผ ์ฝ๊ณ , ์ฌ๋ฐ๊ฒ ๋ฐฐ์ฐ๊ณ ์ถ์ ๋ชจ๋  ๋ถ๋ค**์ ์ํด ๋ง๋ค์ด์ก์ต๋๋ค.

<br><br>

## ๐บ ์์ฐ์์

> ์ฌ์ง์ ํด๋ฆญํ๋ฉด ์ ํ๋ธ ํ์ด์ง๋ก ์ด๋ํฉ๋๋ค

<p align='middle'><a href="https://www.youtube.com/watch?v=qbOyOyLsYps" target="_blank"><img src="https://user-images.githubusercontent.com/26705587/174591455-754f48ae-32dc-423e-9b6e-55907de5d3a4.JPG" width="600px"/></a></p>

<br><br>

## โ ๊ธฐ์  ์คํ

### ๐ปBack-End

#### ํ๋ ์์ํฌ

- Django - 3.2.5
- djangorestframework(DRF) - 3.12.4

#### ๋ผ์ด๋ธ๋ฌ๋ฆฌ

- djangorestframework-simplejwt - 4.8.0
- dj-rest-auth - 2.1.11
- PyMySql - 1.0.2
- ์ด์ธ์ ์์ธํ ๋ผ์ด๋ธ๋ฌ๋ฆฌ๋ [requirements.txt](./Back/django-game/requirements.txt) ์ฐธ์กฐ

</br>

### โจFront-End

#### ํ๋ ์์ํฌ

- Vue.js - 2.6.14

#### ๋ผ์ด๋ธ๋ฌ๋ฆฌ

- axios - 0.21.1
- vuex - 3.6.2
- vue-router - 3.5.2
- ์ด์ธ์ ์์ธํ ๋ผ์ด๋ธ๋ฌ๋ฆฌ๋ [package.json](./Front/client/package.json) ์ฐธ์กฐ

</br>

### ๐พ Machine Learning

#### ํ๋ ์์ํฌ

- TensorFlow.js - 3.9.0

#### ๋ผ์ด๋ธ๋ฌ๋ฆฌ(๋ชจ๋ธ)

- [fingerpose](https://github.com/andypotato/fingerpose#readme) - 0.0.2
- [tensorflow-models/handpose](https://github.com/tensorflow/tfjs-models#readme) - 0.0.7

<br><br>

## ๐จ  ์ค์น ๋ฐ ์คํ๋ฐฉ๋ฒ

#### ํด๋๊ตฌ์กฐ

```
๐ Front				# ํ๋ก ํธ 
๐ Back					# ๋ฐฑ์๋ 
๐ AI					# ์ธ๊ณต์ง๋ฅ
```

</br>

#### ํ๋ก์ ํธ ์คํ๋ฐฉ๋ฒ(Local ๊ธฐ์ค)

> ๊ฐ ํด๋ ๋ณ๋ก ์คํ ์์ผ์ผ ํฉ๋๋ค.

##### โBack-End

###### 1) Back/django-game/ ์ผ๋ก ์ด๋ํ๋ค.

###### 2) ํฐ๋ฏธ๋์ฐฝ์ ์ด์ด ๋ค์๊ณผ ๊ฐ์ด ์๋ ฅํ์ฌ ๊ฐ์ํ๊ฒฝ์ ๋ง๋ ๋ค.

```bash
python -m venv venv
```

###### 3) ๋ค์๊ณผ ๊ฐ์ด ์๋ ฅํ์ฌ ๊ฐ์ํ๊ฒฝ์ ํจ๋ค.

```bash
source venv/Scripts/activate
```

###### 4) (์ฒ์ ์คํ์์๋ง) ๋ค์๊ณผ ๊ฐ์ด ์๋ ฅํ์ฌ ํ์ํ package๋ฅผ ํ์ฌ ๊ฐ์ํ๊ฒฝ์์ ์ค์นํ๋ค.

```bash
pip install -r requirements.txt
```

###### 5) Django ์๋ฒ๋ฅผ ํจ๋ค.

```bash
python manage.py runserver
```

</br>

##### โFront-end

###### 1) .env.local ํ์ผ์ Front/client/ ๊ฒฝ๋ก์ ๋ง๋ ๋ค.

###### 2) .env.local์ ์ด์ด ์๋ ๋ด์ฉ์ ๋ถ์ฌ๋ฃ๋๋ค.(๊ธฐ๋ณธ์ผ๋ก ์ผ์ง ๋ก์ปฌํธ์คํธ ์ฃผ์)

```
VUE_APP_SERVER_URL = http://127.0.0.1:8000
```

###### 3) Front/client/ ๊ฒฝ๋ก์์ ํฐ๋ฏธ๋์ฐฝ์ ํจ๋ค.

###### 4) (์ฒ์ ์คํ์์๋ง) ๋ค์๊ณผ ๊ฐ์ด package๋ฅผ ์ค์นํ๋ค.

```bash
npm install
```

###### 5) ๋ค์๊ณผ ๊ฐ์ด ํด๋ผ์ด์ธํธ๋ฅผ ๋ก์ปฌ ํ๊ฒฝ์์ ์คํํ๋ค.

```bash
npm run serve
```

</br>



## ๐ฉ์ฃผ์๊ธฐ๋ฅ

1. **๋ฉ์ธํ์ด์ง**

   <img src="https://user-images.githubusercontent.com/26705587/174593133-67e871b2-75c6-4479-b98b-389dccf9a0cf.JPG" height="300px"/>

   <br>

2. **ํ์ตํ๊ธฐ**

   <img src="https://user-images.githubusercontent.com/26705587/174593152-f8b7130d-9c9b-42f2-a16a-4e8c47fb41ba.JPG" height="300px"/>

   <br>

3. **์ฐ์ฑ๋น ๊ฒ์**

   <img src="https://user-images.githubusercontent.com/26705587/174593231-5a15204a-8019-484a-bdfa-f6126a371d66.JPG" height="300px"/>

   <br>

4. **๋จ์ด๋ง์ถ๊ธฐ ๊ฒ์** 

   <img src="https://user-images.githubusercontent.com/26705587/174593213-60013f02-6a20-4fa2-985f-749a77bdb196.JPG" height="300px"/>

   <br>

5. **์นด๋๋ค์ง๊ธฐ ๊ฒ์**

   <img src="https://user-images.githubusercontent.com/26705587/174593260-4f0f3f7a-5fee-470d-b5e9-3798c11ac445.JPG" height="300px"/>

   <br>

6. **๋ช์์ ์ ๋น**

   <img src="https://user-images.githubusercontent.com/26705587/174593303-119f341e-b894-43f4-8c68-3af8d6f62c3a.JPG" height="300px"/>

   <br>

7. **๋ง์ดํ์ด์ง**

   <img src="https://user-images.githubusercontent.com/26705587/174593291-4a39611e-022b-408f-b103-ecda9738baf3.JPG" height="300px"/>

   <br><br><br>



## ๐WIKI

๐[B306ํ์ ํ์๋ฐฉ๋ฒ ๋ณด๋ฌ๊ฐ๊ธฐ](https://github.com/hataerin/AKSOO/wiki)๐

๐[ํ๋ก์ ํธ ์๊ฐ](./์์_์๊ฐ.pdf)๐

