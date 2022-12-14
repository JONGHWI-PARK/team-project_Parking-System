![image](https://user-images.githubusercontent.com/100775231/196356837-c4dbd6d2-9bc2-4cf2-8a54-b3c4d5a3bd53.png)

<br>

# ๐ team-project_Parking-System
> - ์ฃผ์ฐจ์ฅ ๊ด๋ฆฌ ํ๋ก๊ทธ๋จ : ์ ๊ธฐ๊ถ๊ณผ ์ผํ๊ถ์ ๋ฐ๋ฅธ ์ฃผ์ฐจ์ฅ ์์ถ์ฐจ ๊ด๋ฆฌ ํ๋ก๊ทธ๋จ
> - ๊ตญ๋น ๊ต์ก ๊ณผ์  ์ด์ ์ค์ ์ ๊ท ํ๋ก์ ํธ ์ธ์ ์คํฐ๋์๋ค๊ณผ Java ํ ์ด ํ๋ก์ ํธ ์งํ

</br>

## 1. ์ ์ ๊ธฐ๊ฐ & ์ฐธ์ฌ ์ธ์
- 2022๋ 05์ 12์ผ ~ 2022๋ 06์ 05์ผ
- ํ ํ๋ก์ ํธ (5๋ช)

</br>

## 2. ํ์ ์๊ฐ
์กฐ์ฅ : ๊น์์ฐ <br>
์กฐ์ : ๋ฌธ๊ธฐ์ฐ, ๋ฐ์ขํ, ๊น๊ฐ์, ๋ฐ์ง์ค

> ๋ฉ์ธ ํด๋์ค, DBMS / DBMS ์ฐ๊ฒฐ ํด๋์ค, ๋ฐํ - ๊น์์ฐ <br>
> ์ด(ํ์ฌ) ์ฃผ์ฐจ ํํฉ ํด๋์ค - ๋ฌธ๊ธฐ์ฐ, ๊น๊ฐ์ <br>
> ์ ๊ธฐ๊ถ ์ฐจ๋ ํํฉ ํด๋์ค - ๋ฐ์ขํ <br>
> ์์ถ์ฐจ ํด๋์ค - ๊น๊ฐ์, ๋ฐ์ง์ค <br>
> ๊ฒฐ์  ํด๋์ค - ๋ฌธ๊ธฐ์ฐ <br>
> ํผํผํฐ ์ ์ - ๋ฐ์ง์ค <br>

<br>

## 3. ๋ด๋นํ ํํธ
- ์ ๊ธฐ๊ถ (CommutationTicket Class) : ๐ [์ฝ๋ ํ์ธ](https://github.com/JONGHWI-PARK/team-project_Parking-System/blob/master/src/parking_lot/CommutationTicket.java)
  - ํ์ ์ ๋ณด๋ฅผ ์๋ ฅ๋ฐ์ผ๋ฉด DB CommutationTicket ํ์ด๋ธ์ ๋ฐ์ดํฐ๊ฐ ์ ์ฅ๋๋๋ก ๊ตฌํ
  - DB์์ ๋ฐ์ดํฐ๋ฅผ ๊ฐ์ ธ์ size()๋ฅผ ํ์ฉํ์ฌ ์ ๊ธฐ๊ถ ์๋ ์กฐํ ๊ตฌํ
  - ์ ๊ทํํ์์ ์ฌ์ฉํ์ฌ ํ์ ์ ๋ณด์ ์ ํจ์ฑ๊ฒ์ฌ ์งํ
  
<br>

## 4. ์ฌ์ฉ ๊ธฐ์ 
#### `Language`
  - Java 8
  - Oracle SQL
#### `Tool`
  - Eclipse
  - DBeaver

<br>

## 5. ERD ์ค๊ณ ๋ฐ User Flow

![](https://velog.velcdn.com/images/jack_whiteblack/post/01278883-a5bf-42c8-9060-23285093da18/image.png)

![](https://velog.velcdn.com/images/jack_whiteblack/post/b55fff8e-7c4e-4a4d-9e68-0f7f4d87e2bd/image.png)

<br>

## 6. ๊ตฌ์ฑ

![](https://velog.velcdn.com/images/jack_whiteblack/post/dfbcca8d-57fc-46f8-a71e-aee1c61d0d45/image.png)

<details>
<summary><b>4-1. ์ฃผ์ฐจ์ฅ ๊ด๋ จ Class : ์ด 6๊ฐ์ Class๋ก ์ด๋ฃจ์ด์ ธ ์๋ค.</b></summary>
<div markdown="1">
- ParkingMain(Main)<br>
- TotalParking(์ด(ํ์ฌ) ์ฃผ์ฐจ ํํฉ)<br>
- Inout(์์ถ์ฐจ)<br>
- CommutationTicket(์ ๊ธฐ๊ถ)<br>
- Payment(๊ฒฐ์ )<br>
- Ending(์ข๋ฃ)<br>
</div>
</details>

<details>
<summary><b>4-2. ๋ฐ์ดํฐ๋ฒ ์ด์ค ๊ด๋ จ Class : ์ด 4๊ฐ์ Class๋ก ์ด๋ฃจ์ด์ ธ ์๋ค.</b></summary>
<div markdown="1">
- AuthenException<br>
- DAO<br>
- DBConn<br>
- ParkingDTO<br>
</div>
</details>

<details>
<summary><b>4-3. SQL Table : ์ด 4๊ฐ์ Table๋ก ์ด๋ฃจ์ด์ ธ ์๋ค.</b></summary>
<div markdown="1">
- TOTALPARKING<br>
- COMMUTATIONTICKET<br>
- ENTRANCE<br>
- ONETIMETICKET<br>
</div>
</details>

<br>

## 7. ์์ฐ ์์

### โ ์ ๊ธฐ๊ถ ๋ฑ๋ก + ๊ฒฐ์ 
![](https://velog.velcdn.com/images/jack_whiteblack/post/1e741b66-0b1b-40f7-8e2f-d982575d26aa/image.gif)

### โ ์์ฐจ (์ ๊ธฐ๊ถ)
![](https://velog.velcdn.com/images/jack_whiteblack/post/1d5050e9-7f8b-4f1e-8f63-c45220c53ef9/image.gif)

### โ ์์ฐจ (์ผํ๊ถ)
![](https://velog.velcdn.com/images/jack_whiteblack/post/1b61aa69-d871-461d-b6c2-61058d9aa7a7/image.gif)

### โ ์ถ์ฐจ
![](https://velog.velcdn.com/images/jack_whiteblack/post/f1e4d4bf-63a2-47df-b49e-91a911950c5b/image.gif)

### โ ์ฃผ์ฐจํํฉ + ํ๋ก๊ทธ๋จ ์ข๋ฃ
![](https://velog.velcdn.com/images/jack_whiteblack/post/2befa0ea-2ee7-4c0c-a910-e19a9f1a6bf3/image.gif)

<br>

## 8. ํ๋ก์ ํธ ํ๊ธฐ
ํ ํ๋ก์ ํธ๋ ์ํต์ด ๊ฐ์ฅ ์ค์ํ๋ค๋ ๊ฒ์ ๋ค์ ํ๋ฒ ๋๊ผ๋ค. ์๋ก ๋ชจ์ฌ์ ์ค๋ฅ๋ฅผ ์์ ํด๋๊ฐ๋ ๊ณผ์ ์์ ์ ๋ง ๋ง์ ์๊ฒฌ์ ๋๋ด๊ณ  ๋ชจ๋ฅด๋ ๋ถ๋ถ์ ๊ตฌ๊ธ๋ง์ ํด๊ฐ๋ฉฐ ๊ฐ์ด ์ด๋ ค์์ ํค์ณ ๋๊ฐ๋ค. ๊ทธ๋ฌ๋ค ๋ณด๋ ํผ์ ํ  ๋ ๋ณด๋ค ๋ ๋ค์ํ ์๋ฃจ์๋ค์ด ๋์๊ณ  ์กฐ๊ธ ๋ ์์ฑ๋ ๋์ ๊ฒฐ๊ณผ๋ฅผ ์ป์ ์ ์์๋ค. 
<br>
ํ ํ๋ก์ ํธ๋ ํผ์ ํ๋ ๊ฒ์ด ์๋๊ธฐ์ ์๊ธฐ์ ์ฃผ์ฅ์ ๋ฌด์กฐ๊ฑด ๋ฐ๊ณ  ๋๊ฐ๋ ๊ฒ์ด ์๋๋ผ ๋ค๋ฅธ ์ฌ๋๋ค๊ณผ ์๊ฒฌ์ ๊ณต์ ํ๋ฉด์ ์กฐ๊ธ ๋ ์ ์ ํ ์๋ฃจ์์ ์ฐพ์ ์ ์๋ค๋ ๊ฒ์ ์ด๋ฒ ํ๋ก์ ํธ ํ๋ฉด์ ๋ค์ ํ๋ฒ ๋๋ผ๊ฒ ๋์๋ค.

<br>

> - ํ๋ก์ ํธ ๊ฐ๋ฐ ๊ด๋ จ ๊ธ : [์๊ฐ์ด ์ง๋๋ฉด ๊ฒฌ์ธํ์กฐ - ์ฃผ์ฐจ์ฅ ํ๋ก๊ทธ๋จ ํ๋ก์ ํธ](https://velog.io/@jack_whiteblack/%EC%8B%9C%EA%B0%84%EC%9D%B4-%EC%A7%80%EB%82%98%EB%A9%B4-%EA%B2%AC%EC%9D%B8%ED%95%98%EC%A1%B0-%EC%A3%BC%EC%B0%A8%EC%9E%A5-%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%A8-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8)
> - ํ๋ก์ ํธ ๊ทธ ํ : [ํ๋ก์ ํธ ๊ทธ ํ - ์ฃผ์ฐจ์ฅ ๊ด๋ฆฌ ํ๋ก๊ทธ๋จ](https://velog.io/@jack_whiteblack/%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%EA%B7%B8-%ED%9B%84-%EC%A3%BC%EC%B0%A8%EC%9E%A5-%EA%B4%80%EB%A6%AC-%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%A8)
