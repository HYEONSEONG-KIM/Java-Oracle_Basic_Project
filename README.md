# Java&Oracle Basic Project

## 제안배경

- 영화 예매 시스템 구축
- Java JDBC API를 이용하여 Oracle DB와 연동
- 별도의 UI가 없는 Consol Project로 진행
- 데이터의 CRUD를 중점으로 프로젝트 진행
- 대덕인재개발원 1차 Project

## 개발기간 & 구성원

- 2021-03-26 ~ 2021-04-05

- Team Member : 김영광, 김현성, 이기정, 최진우(4명)



## 개발환경

![image](https://user-images.githubusercontent.com/70748105/113528403-70661400-95fb-11eb-9008-604dbc67bdf9.png)



## 메뉴 구성도

## ![image](https://user-images.githubusercontent.com/70748105/113526799-5970f300-95f6-11eb-8f06-40a48b60cc97.png)

![image](https://user-images.githubusercontent.com/70748105/113526883-a9e85080-95f6-11eb-9eda-63206594d6ef.png)



## DB설계

### 개념적 설계 (ERD)

![erd-1](https://user-images.githubusercontent.com/70748105/113526225-2cbbdc00-95f4-11eb-829b-1343118b3fae.PNG)

![erd-2](https://user-images.githubusercontent.com/70748105/113526237-3a716180-95f4-11eb-97e9-740b0bee34ed.PNG)



## ### 논리적 설계

![image](https://user-images.githubusercontent.com/70748105/113526980-f2077300-95f6-11eb-9b28-79b3431dae0d.png)



### 물리적 설계

![image](https://user-images.githubusercontent.com/70748105/113527010-0ba8ba80-95f7-11eb-82b5-75914abefb06.png)



## ## 기능 - 사용자

### 1.예매

- 사용자는 원하는 지역 선택
- 지역 선택 후 원하는 지점 선택
- 상영 시간표(상영시각이 지난 시간표는 출력되지 않음)를 보고 원하는 시간대의 영화 선택
- 해당 상영 정보의 좌석 현황보고 예매 진행   
- 결제 방식은 미리 충전해 놓은 캐쉬를 이용하여 진행  
- ![image](https://user-images.githubusercontent.com/70748105/113527066-44e12a80-95f7-11eb-82ca-e75ebcf704e2.png)

### 2.마이페이지

- 내 정보보기, 예매 내역, 캐쉬 충전, 회원탈퇴 등으로 구성  

  ![image](https://user-images.githubusercontent.com/70748105/113527333-2f203500-95f8-11eb-934a-a3cb27d328db.png)

### 3.게시판

- 리뷰 게시판 목록, 리뷰 작성, 리뷰 조회, 평점 조회 등으로 구성  
- ![image](https://user-images.githubusercontent.com/70748105/113527304-1a43a180-95f8-11eb-824d-83895e4c724f.png)



### 4.푸드 코트

- 장바구니, 결제 등으로 구성

  ![image](https://user-images.githubusercontent.com/70748105/113527565-f6349000-95f8-11eb-86a0-12e556c0cbeb.png)

## 기능 - 관리자

### 1.상영 중 영화 관리

- 현재 상영중인 영화 삭제 및 새로운 영화 등록

![image](https://user-images.githubusercontent.com/70748105/113527773-85da3e80-95f9-11eb-9f59-3d4d51c59556.png)

### 2.상영리스트 관리

- 상영날짜가 지난 상영리스트 한 번에 삭제
- 지역 -> 지점 선택 후 해당 지점의 상영 리스트 등록 및 삭제  

![image](https://user-images.githubusercontent.com/70748105/113527850-ccc83400-95f9-11eb-86d7-0e3ec4db9b33.png)



### 3.영화 리뷰 관리

- 사용자가 작성한 리뷰글 및 게시글 관리  

![image](https://user-images.githubusercontent.com/70748105/113527939-17e24700-95fa-11eb-94ac-bec6bc6a30ac.png)
