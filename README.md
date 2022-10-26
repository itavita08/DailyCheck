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


은혜선


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

은혜선


최소영
- 회원 관리 기능 에러 수정
- 게시물 생성 기능과 회원정보기능 합치고 확인
- AWS 환경 구축
