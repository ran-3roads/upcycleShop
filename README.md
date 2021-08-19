# 재활용 수제품 쇼핑몰 -jsp

## 1. 개요

<img width="769" alt="1" src="https://user-images.githubusercontent.com/66467266/130023639-b2340ea2-85b9-42b5-9780-591bfed80699.png">




jsp를 사용하여 만든 쇼핑몰 홈페이지 입니다. 소비자들에게 펀딩을 받고 폐마스크, 병뚜껑, 페트병과 같은 집안에서 나오는 쓰레기들을 업사이클링하여  판매하는 수제품 쇼핑몰입니다

## 2. 기술

1. Web Front : `HTML5` , `CSS`, `JavaScript`

   Web Server : `Java`, `ApacheTomcat`

2. DBMS : `MySQL`

3. 개발환경 : `Eclipse`

## 3. database

* 게시판 DB
  * 게시글 번호: st_id
  * 게시글 작성자 아이디: Id
  * 게시글 작성자 이름:st_name
  * 게시글 제목: st_title
  * 작성일: st_date
  * 게시글 분류: st_category
  * 게시글 내용: st_content
  * 게시글 비밀번호: st_pw
  * 게시글 이미지 이름: st_img
  * 게시글 펀딩 진행도: st_funding
* 유저 DB
  * 유저 아이디: userId
  * 유저 비밀번호: userPassword

## 4. 사이트맵

<img width="780" alt="2" src="https://user-images.githubusercontent.com/66467266/130023642-f66078fd-c1a7-4fd4-a88b-6a39d7cf3a9e.png">

## 5. 기능

1. 회원가입/로그인
2. 게시물 CRUD
5. 게시물 펀딩
7. 게시판 검색
5. 상품 구매/판매
