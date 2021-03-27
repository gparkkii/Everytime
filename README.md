# Everytime board clone
<br/>
<p align="center">
  <a href="https://everytime.kr/">
    <img width="180" alt="7" src="https://user-images.githubusercontent.com/71811780/108621851-815a2c00-7478-11eb-88f4-be10f3320809.png">
  </a>
</p>

## Description
학교 커뮤니티 서비스인 에브리타임 게시판 클론 프로젝트입니다.MongoDB, Express.js, React.js, Node.js 스택을 활용해 CRUD 기능을 구현하고 REST API 개발역량과 팀 협업 능력을 키우는 것을 목표로 했습니다.

<br/>

## Preview
#### 로그인 & 회원가입
<p align="center">
  <img width="280" alt="7" src="https://user-images.githubusercontent.com/71811780/108114998-e01c5000-70dc-11eb-97d2-de160f368d5a.gif">
  &nbsp;&nbsp;&nbsp;
  <img width="280" alt="7" src="https://user-images.githubusercontent.com/71811780/108112315-44d5ab80-70d9-11eb-8595-eda8af5d9d76.gif">
</p>

#### 게시판 & 마이페이지
<p align="center">
  <img width="280" alt="7" src="https://user-images.githubusercontent.com/71811780/108112312-43a47e80-70d9-11eb-8b93-b34216d96f22.gif">
  &nbsp;&nbsp;&nbsp;
  <img width="280" alt="7" src="https://user-images.githubusercontent.com/71811780/108112317-4606d880-70d9-11eb-939f-64ee09f484da.gif">
</p>

<br/>

## Features
#### 공통
1. HOC를 사용하여 페이지별 접근 인증
2. Redux를 통한 상태관리

#### 로그인
1. JWT 인증방식을 이용한 로그인
2. 로그인 시 ID, PW의 일치여부 체크 

#### 회원가입
1. 아이디 중복체크
2. 아이디 및 비밀번호 글자 수 제한
3. 학교 검색 및 학번 추가 기능
4. 필수정보 입력 여부 확인 후 가입 승인

#### 게시판
1. 프로필에 로그인한 user 정보 표시
2. 게시판 글 작성 및 익명 기능 구현
3. 게시글 작성시간 표시 및 desc 정렬
4. 좋아요 및 댓글 기능 추가
5. Pagination 구현

#### 마이페이지
1. 계정 정보 변경 기능 (닉네임, 이메일, 비밀번호 변경)
2. 내가 쓴 게시글, 댓글 및 좋아요 관리 메뉴
3. 내가 쓴 게시글 및 댓글 삭제 기능
4. 회원탈퇴 시 user의 모든 정보 삭제

<br/>

## Contributors

박지연 [Github](https://github.com/gparkkii)<br/>
송보은 [Github](https://github.com/Boeun05)

#### UI/UX
- 박지연, 송보은 

#### Frontend
  - 송보은 : 로그인, 회원가입, 마이페이지
  - 박지연 : 게시판, 마이페이지
 
#### Backend
  - 박지연 : 로그인, 회원가입, 게시판, 마이페이지

<br/>

## Requirements

### Language
- Frontend
  - Javascript
  
- Backend
  - Node.js
  
### Framework
- Frontend
  - React
  
- Backend
  - Express.js
  
### Database
- MongoDB 

### Library
- Frontend
  - Redux
  - React-Router
  - Styled-components
  - Axios
  - @material-ui/lab

- Backend
  - Mongoose
  - Bcrypt
  - JWT
