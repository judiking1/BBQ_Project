# BBQ_Project
조별 자바 프로젝트 CRUD

#1. 개요
프론트 엔드와 백엔드를 모두 활용 할 수 있는 웹페이지를 찾아 구현해 보았습니다.
프로젝트를 통해 소통하며 협업하는 방법을 배우며, 프론트 엔드와 백엔드 각 포지션을 나눠서 오류없이 페이지를 구현했습니다.

#2. DB 구성
[Floatleft_Project_BBQ.txt](https://github.com/tjsrbkR/Team-BBQ/files/11876879/Floatleft_Project_BBQ.txt)


#3. 구성
# Project 명
  : Floatleft_Project_BBQ
   => BBQ 사이트 구현 실습
   => Model1 방식
   
# Project DB접속방식
  : JDBC 이용
  
## Project Hieracital
a. 자바패키지
   biz > board + common + user + menu + order
b. webapp 폴더
   css + images + include + js + login_join + order

#4. Work-Flow
[Floatleft_Project_BBQmd.TXT](https://github.com/tjsrbkR/Team-BBQ/files/11876906/Floatleft_Project_BBQmd.TXT)


#5. 프로젝트 시연  

<h2>로그인, 회원가입, 주문</h2>

https://github.com/tjsrbkR/Team-BBQ/assets/97294091/7482ad80-0bd8-4192-a516-dfb4d49c2b60

<h2>관리자 페이지, 답변 </h2>

https://github.com/tjsrbkR/Team-BBQ/assets/97294091/ef2972d7-5dbf-43b4-bd4c-dbf1c97b2088

<h2>글작성,수정, 개인정보 변경</h2>

https://github.com/tjsrbkR/Team-BBQ/assets/97294091/795b24eb-afa9-45ac-a389-0ffc3b497cda

<h2>답변확인</h2>

https://github.com/tjsrbkR/Team-BBQ/assets/97294091/ae3988b3-dd88-4ae8-82f1-85edbdae860c

<h2>메뉴정보</h2>

https://github.com/tjsrbkR/Team-BBQ/assets/97294091/9711824b-bc14-4dd4-b426-dc71c4dc2c34

<h2>매장찾기</h2>

https://github.com/tjsrbkR/Team-BBQ/assets/97294091/2bdab9ca-b4e8-4a4f-a0ee-420a340f3565


구성 :
 Main (index)
 Sub (메뉴 소개)
 Contents (각 메뉴 클릭시 메뉴 정보)
 Etc (회원가입, 로그인, 온라인주문, 고객문의, 마이페이지, 관리자페이지 등)

마이페이지 :
 1. 포인트, 쿠폰, 주문 내역, 문의 내역, 문의에 달린 관리자 답글 확인 가능
 2. 답글 달리기전에 문의 삭제 가능
 3. 개인정보변경 가능

주소찾기 기능( 카카오 오픈소스 이용 ) :
 1. 메인페이지 GNB의 매장찾기 페이지, 매장 안내 box
 2. 회원 가입시 매장찾기
 3. 마이페이지의 주소록
 4. 고객문의시 매장찾기

관리자* 페이지** : 모든 회원 목록, 주문내역, 문의내역 확인가능. 문의내역에 답변 가능
* 관리자 아이디는 DB에서 따로 insert 하여 만들어야 함.
** 상단 우측 메뉴는 일반회원은 마이페이지, 관리자는 관리자페이지로 구분됨.
