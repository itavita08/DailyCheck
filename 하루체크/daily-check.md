# DailyCheck
---
## 2022-10-21
### Check-In
김영준
- Figma 수정
- Backlog 수정

이명호
- Figma UI/UX 설계
- ERD테이블 재구조화
- front-end 로그인시스템에서 비밀번호 찾기 시스템 구상 후 테스트코드 작성

은혜선
- 피그마 수정 (개인 페이지)
- backlog 작성

최소영
- db ERD 수정
- 피그마 수정 (글 작성, 사이드바 등 세부 수정)
---
## 2022-10-24
### Check-In
김영준
- 게시글 - 글 작성 기능 front, back (react - flask), board 

이명호
- 로그인 - 비밀번호 찾기 front, back
- 로그인 - 로그인폼 구현(jwt)

은혜선
- 게시글 - 글 작성 기능 front, back (react - flask), board 

최소영
- 회원 정보 관리 - 회원 가입 기능 front, back (email, db를 이용하여 중복 확인 예외 처리 하기)
- 회원 정보 관리 - 로그인 기능 front, back (ATK 만료 확인 후 RTK 서버에 header 로 요청)
- 회원 정보 관리 - 로그아웃 기능

### Check-Out

김영준
- 작성기능은 구현하였지만 세부적인 기능들은 시간안에 완성하지 못해서 아쉽다

이명호
- 아이디찾기까지 되었다. 하지만 비밀번호 찾기폼 구현을 못해서 아쉬웠다.

은혜선
- 게시글 - 글 작성 기능 front, back (react에서 flask로 데이터 보내기 확인)

최소영
- 전체 코드 작성은 완료 했으나, RTK 재발급 이후 original request 에러 해결 하지 못함. 
- back 예외 처리 추가해야 함.
---
## 2022-10-25
### Check-In
김영준
- 게시글 - 글 작성 기능 front, back (react - flask), board 세부기능 마저 마무리
- 글 작성기능 완료 후 spring과 연동해보기

이명호
- DB에 맞춰서 로그인폼 재구조
- node.js(back)-react(front) 방식으로 비밀번호 찾기폼 

은혜선
- react에서 spring boot로 게시글 데이터 넘기기, 형태 확인
- 게시판 부가기능 

최소영
- DB 생성
- DB 에 맞춰 회원 정보 관리 코드 수정

### Check-Out

김영준
- 게시글 - 글작성 기능 모두 구현 후 Flask, React, Spring 서로 연동되어 데이터가 넘어가는거까지 확인하였다
- Spring으로 데이터를 넘길때 json형태를 RequestParam 어노테이션으로 못받는것을 모르고 계속 시도하다가 알게되었다.
- json으로 넘어올때는 RequestBody를 사용하자   
- 졸리다 졸리다 졸리다 졸리다 졸리다 졸리다 졸리다 

이명호
- 재구조는 완료
- 비밀번호 찾기폼은 생각보다 로직이 복잡해서 기본기능 구현후 재도전 해봐야겠음

은혜선
- 게시판 부가기능 설정함
- react에서 spring boot로 String 형태로 데이터 받음,,,DTO로 확인해야함



최소영
- 오늘 해야 할 일은 다 했음 ~~ 
- 근데 refresh token 으로 access token 을 받은 후 original request 에러 문제 아직 해결 못함,,, 강사님이나 멘토님한테 물어봐야겠다,,,,

---
## 2022-10-26
### Check-In
김영준
- 게시물 생성 기능과 회원정보기능 합치고 확인
- AWS 환경 

이명호
- refreshtoken 서버로 res/req 확인
- react로 frontend

은혜선
- react에서 spring으로 DTO로 mapping 
- AWS 환경 

최소영
- 회원 관리 기능 에러 수정
- model DTO, Entity 등 생성
- 게시물 생성 기능과 회원정보기능 합치고 확인
- AWS 환경 구축

### Check-Out
김영준
- 게시물 생성 기능 Spring으로 데이터 보내기 확인
- 게시물 생성 기능과 회원정보 기능 합치기 성공
- DTO, Entity 생성 완료
- 우려했던 메인기능들이 얼추 자리를 잡은거 같아서 만족스럽고 앞으로 부가기능을 구현할때 도움이 많이 될것같다.   
  팀원을 잘 만났다는 것을 또 한번 느끼는 하루였다

이명호


은혜선
- model DTO, Entity 등 생성
- react에서 게시물 db로 insert

최소영
- model DTO, Entity 등 생성 
- 게시물 생성 기능과 회원정보기능 합치기 성공
- AWS EC2 구축, 탄력적 IP 할당, putty 설치 및 AWS 접속, Key.ppk 팀원들에게 나눠줌. 
---

## 2022-10-27
### Check-In
김영준
- spring db연동
- 게시물 상세 페이지
- jwt 리뷰

이명호
- css(로그인,회원가입)
- 차트에 필요한 데이터 정의
- 로그인폼 local에 말고 Cookie저장되는지 확인

은혜선
- 게시물 작성 페이지에서 게시물 상세 페이지로 이동 front, back
- 로그인, 회원가입 관련 코드 파악하기
- 게시물 crud 발이라도 담가보기..? 


최소영
- 회원관리 리액트 코드 수정 하여 완성하기!!!! 꼭!!!! 제발!!!!
- 회원 정보 관리 + 글 작성 코드


### Check-Out

김영준
- 오늘 하고자 한것은 다 한거같다.
- 다음날이 리뷰데이라서 그런지 너무나 긴 하루였다.

이명호
- css로 로그인,회원가입 폼은 완성
- 코드가 합쳐져서 같은 백엔드와 프론트로 작업할 수 있게 되어서 매우 좋다.
- css(GRID)툴이 생각보다 이해하기 오래걸려 그냥 만들어진폼 갖다써야겠다..

은혜선
- 게시물 작성 페이지에서 게시물 상세 페이지로 이동함


최소영
- 회원관리 리액트 코드 에러 해결함. 버전 문제 였음.
- 회원 정보 관리 + 글 작성 코드 합치고 깃에 업로드 함.
---

## 2022-10-31
### Check-In

김영준
- 게시물 CRUD

이명호
- 라우터를 이용한 접근 제한 구현 (Access Control & Authentication) 로그인전후 페이지 구분
- user,guest 페이지 구분

은혜선
- 게시물 CRUD (이미지와 댓글 account 같이)
 
최소영
- 스프링 토큰 변환하여 accountId 받아 각 필요한 메소드에 뿌리기
- 리액트 사이드바, 헤더 페이지 이동 넣기

### Check-Out

김영준
- Spring에서 react로 데이터가 넘어가지 않는다......................... 하루종일했는데...............................
- 시간이 얼마 없어서 빨리해야하는데...........................................

이명호
- 오늘 하루 계획한건 구현해서 기분좋음
- 근데 css다시해야되서 짜증남...

은혜선
- 게시물 insert는 되는데 상세 페이지 이동이 안됨

최소영
- 해야 할 것은 다 했움
- 라우터 다시 공부해보기
- index.js 과 App.js 에 라우터 해야 할 컴포넌트 구분해서 정리해보기
---

## 2022-11-01
### Check-In

김영준
- 게시물 crud 마무리!!!!!!!!!하기

이명호
- 메인페이지 프론트엔드,백엔드

은혜선
- 상세 페이지 이동
- 게시물 crud

 
최소영
- 마이 페이지 백엔드, 프론트엔드
- 페이지 이동 
- 새로고침 문제 해결하기


### Check-Out

김영준
- 금방할 줄 알았던 게시물 CRUD를 오랜시간에 걸쳐서......... 마무리했다.........
- 너무너무 힘들고 사소한 코드 하나로 인해 며칠을 고생한걸 생각하면 눈물이 앞을가린다......


이명호
- react-node.js-mysql 서버 동기화까진 적용했지만 실기능을 구현하지 못했다. 너무 어렵다...
- 자정까지만 더 해봐야겠다.

은혜선
- button의 타입 바꿔서 자동 새로고침 문제 해결.. 약간 어이 없음
- react quill 게시글 수정 불러오려고 몇 시간을 팜, ui 가져와서 쓴건데 작은 기능 하나가 어렵고 시간 참 많이 든다고 느낌

최소영
- 다했음~~

---

## 2022-11-02
### Check-In

김영준
- 좋아요 기능, 메인 페이지 상위 게시판 노출 기능 완료 후 비밀친구 기능 시작하기

이명호
- 게시물 상세보기 페이지 좋아요 - front
- 게시물 CSS작업

은혜선
-  전체 게시물 조회 spring - 페이지 

최소영
- 검색 기능, 페이지 이동, 페이징 

### Check-Out

김영준
- 좋아요 기능 완성, 상위 게시판 노풀 기능 백엔드 완료!!!!!!! 내일 차트해야지

이명호


은혜선
- 전체 게시물 조회 기능 spring - 페이지 react 
- react pagination ui 설치 후 적용함

최소영
다했333333333333333333

---

## 2022-11-03
### Check-In

김영준
- react 차트 api 찾구 더미데이터 생성 후 차트 적용 시키기!!! 

이명호
- 로그인,회원가입 폼 실구현 폼으로 완벽히 구현 + CSS
- 메인페이지 상위3개 게시물 - front

은혜선
- 비밀 게시판 관련 기능 , 페이지 구현

최소영
- 비밀 페이지 스프링, 리액트 
  - 비밀 게시판 생성(비밀친구 맺음), 비밀 메인 페이지(비밀게시판, 두명의 프로필 정보, 글쓰기 버튼), 비밀 게시물 

### Check-Out

김영준
- 데이터가 다양하지 않아 어떤 차트를 해야할지 생각하는데만 시간을 다 쓴거같다.
- 그래도 얼추 잡아놨으니 내일 끝내야겟다

이명호


은혜선
- 코드 합치기
- 게시물 상세페이지 유저 정보 반환으로 수정
- 모달 창으로 비밀친구 신청 페이지 생성

최소영
- 비밀 관련 기능 백엔드 스프링 코드 작성함.
- 어느정도 API 거의 완성되어서 기쁘다~~

---

## 2022-11-04
### Check-In

김영준
- 오늘 차트 마무리 

이명호

은혜선
- 공유 기능 & 페이지 구현
- css  

최소영
- 스프링 API 예외처리


### Check-Out
김영준
- 차트 오래 걸릴 줄 알았는데 생각보다 금방 끝나서 다행이다.
-  

이명호


은혜선
- 친구 신청 , 알림, 수락, 공유 친구 목록 페이지 구현
- 위와 관련한 spring code 수정


최소영
- 400, 401, 403, 405, 500 에러 처리 완료
- custom 예외처리 완료
---

## 2022-11-05
### Check-In

김영준

이명호 

은혜선 
- 비밀 게시물 관련 페이지 구성

최소영
- aws 환경구축

### Check-Out
김영준

이명호 

은혜선 
- 비밀 게시물 관련 페이지 구성 완
- css는 미완  


최소영
- ec2 스프링 톰켓, rds 완료

## 2022-11-07
### Check-In
김영준
- flask aws 서버 구축

이명호
- swagger ui 적용

은혜선
- sidebar user admin 구분
- 게시물 css 적용

최소영
- ec2 spring 배포
- ec2 리액트 배포
- redis 구축

### Check-Out
김영준
- flask서버 구축은 성공하였으나 GPU없는 인스턴스로 해서 그런지 모델을 실행시키면 서버가 강제 종료됐다.
- react와 연동만 하고 모델을 사용한 인스턴스는 최대한 늦게 해야겠다.

이명호
- swagger ui 적용은 완료 세부적인 내용 구축

은혜선
- sidebar user admin 구분
- 게시물 css 적용
- 
최소영
- ec2 spring, 리액트 독자적으로 배포는 성공했으나, 둘 사이의 연동을 아직 못해봄. 집 가서 해보겠습니다~
- redis 구축 완료

---

## 2022-11-08
### Check-In
김영준


이명호
- css 상세보기 마무리
- swagger ui 명세서 정리

은혜선


최소영
- AWS 구축 Spring, flask, react, db 연동
- flask 서버 제어 버튼 

### Check-Out
김영준


이명호

은혜선


최소영
- 어떻게든 react, spring, , flask, mysql, redis 배포 완료
- flask 서버 제어 버튼은 내일의 나에게,,,,

---


