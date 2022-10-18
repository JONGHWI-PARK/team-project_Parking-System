![image](https://user-images.githubusercontent.com/100775231/196356837-c4dbd6d2-9bc2-4cf2-8a54-b3c4d5a3bd53.png)

<br>

# 🚗 team-project_Parking-System
> - 주차장 관리 프로그램 : 정기권과 일회권에 따른 주차장 입출차 관리 프로그램
> - 국비 교육 과정 이수 중에 정규 프로젝트 외에 스터디원들과 Java 토이 프로젝트 진행

</br>

## 1. 제작 기간 & 참여 인원
- 2022년 05월 12일 ~ 2022년 06월 05일
- 팀 프로젝트 (5명)

</br>

## 2. 팀원 소개
조장 : 김시우 <br>
조원 : 문기연, 박종휘, 김강영, 박지윤

> 메인 클래스, DBMS / DBMS 연결 클래스, 발표 - 김시우 <br>
> 총(현재) 주차 현황 클래스 - 문기연, 김강영 <br>
> 정기권 차량 현황 클래스 - 박종휘 <br>
> 입출차 클래스 - 김강영, 박지윤 <br>
> 결제 클래스 - 문기연 <br>
> 피피티 제작 - 박지윤 <br>

<br>

## 3. 담당한 파트
- 정기권 (CommutationTicket Class) : 📌 [코드 확인]()
  - 회원 정보를 입력받으면 DB CommutationTicket 테이블에 데이터가 저장되도록 구현
  - DB에서 데이터를 가져와 size()를 활용하여 정기권 수량 조회 구현
  - 정규표현식을 사용하여 회원 정보의 유효성검사 진행
  
<br>

## 4. 사용 기술
#### `Language`
  - Java 8
  - Oracle SQL
#### `Tool`
  - Eclipse
  - DBeaver

<br>

## 5. ERD 설계 및 User Flow

![](https://velog.velcdn.com/images/jack_whiteblack/post/01278883-a5bf-42c8-9060-23285093da18/image.png)

![](https://velog.velcdn.com/images/jack_whiteblack/post/b55fff8e-7c4e-4a4d-9e68-0f7f4d87e2bd/image.png)

<br>

## 4. 구성

![](https://velog.velcdn.com/images/jack_whiteblack/post/dfbcca8d-57fc-46f8-a71e-aee1c61d0d45/image.png)

<details>
<summary><b>4-1. 주차장 관련 Class : 총 6개의 Class로 이루어져 있다.</b></summary>
<div markdown="1">
- ParkingMain(Main)<br>
- TotalParking(총(현재) 주차 현황)<br>
- Inout(입출차)<br>
- CommutationTicket(정기권)<br>
- Payment(결제)<br>
- Ending(종료)<br>
</div>
</details>

<details>
<summary><b>4-2. 데이터베이스 관련 Class : 총 4개의 Class로 이루어져 있다.</b></summary>
<div markdown="1">
- AuthenException<br>
- DAO<br>
- DBConn<br>
- ParkingDTO<br>
</div>
</details>

<details>
<summary><b>4-3. SQL Table : 총 4개의 Table로 이루어져 있다.</b></summary>
<div markdown="1">
- TOTALPARKING<br>
- COMMUTATIONTICKET<br>
- ENTRANCE<br>
- ONETIMETICKET<br>
</div>
</details>

<br>

## 5. 시연 영상

### ✔ 정기권 등록 + 결제
![](https://velog.velcdn.com/images/jack_whiteblack/post/1e741b66-0b1b-40f7-8e2f-d982575d26aa/image.gif)

### ✔ 입차 (정기권)
![](https://velog.velcdn.com/images/jack_whiteblack/post/1d5050e9-7f8b-4f1e-8f63-c45220c53ef9/image.gif)

### ✔ 입차 (일회권)
![](https://velog.velcdn.com/images/jack_whiteblack/post/1b61aa69-d871-461d-b6c2-61058d9aa7a7/image.gif)

### ✔ 출차
![](https://velog.velcdn.com/images/jack_whiteblack/post/f1e4d4bf-63a2-47df-b49e-91a911950c5b/image.gif)

### ✔ 주차현황 + 프로그램 종료
![](https://velog.velcdn.com/images/jack_whiteblack/post/2befa0ea-2ee7-4c0c-a910-e19a9f1a6bf3/image.gif)

<br>

## 6. 프로젝트 후기
팀 프로젝트는 소통이 가장 중요하다는 것을 다시 한번 느꼈다. 서로 모여서 오류를 수정해나가는 과정에서 정말 많은 의견을 나눴고 모르는 부분은 구글링을 해가며 같이 어려움을 헤쳐 나갔다. 그러다 보니 혼자 할 때 보다 더 다양한 솔루션들이 나왔고 조금 더 완성도 높은 결과를 얻을 수 있었다. 
<br>
팀 프로젝트는 혼자 하는 것이 아니기에 자기의 주장을 무조건 밀고 나가는 것이 아니라 다른 사람들과 의견을 공유하면서 조금 더 적절한 솔루션을 찾을 수 있다는 것을 이번 프로젝트 하면서 다시 한번 느끼게 되었다.

<br>

> - 프로젝트 개발 관련 글 : [시간이 지나면 견인하조 - 주차장 프로그램 프로젝트](https://velog.io/@jack_whiteblack/%EC%8B%9C%EA%B0%84%EC%9D%B4-%EC%A7%80%EB%82%98%EB%A9%B4-%EA%B2%AC%EC%9D%B8%ED%95%98%EC%A1%B0-%EC%A3%BC%EC%B0%A8%EC%9E%A5-%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%A8-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8)
> - 프로젝트 그 후 : [프로젝트 그 후 - 주차장 관리 프로그램](https://velog.io/@jack_whiteblack/%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%EA%B7%B8-%ED%9B%84-%EC%A3%BC%EC%B0%A8%EC%9E%A5-%EA%B4%80%EB%A6%AC-%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%A8)
