## BOBryTime Backend

밥브리타임 RESTful API Back-end Server 구현하기 😉

#### Back-end : Django + MySQL + Docker

-   [x] MySQL DB와의 연동 (Board, Article, and Comments)
-   [x] 일부 버그 Fix (실행 안되던 문제)
    -   MySQL 8.x 버전대라서, Password 암호화 관련 인증하는 방식을 변경함
    -   오탈자 👉 비밀번호가 잘못 적혀있는 부분을 수정
    -   `django-cors-headers` 패키지가 설치되지 않았던 부분 수정
-   [x] RESTful API Endpoint 설계
-   [x] Front-end와의 동기화
-   [x] 나머지 Rule 및 Filter Setting
-   [x] ELK Stack과 Log 연동

#### 추가로 구현하면 좋을법한 기능들

-   [ ] 회원가입/로그인 기능
-   [ ] 유저정보 수정
-   [ ] 공감/비공감 기능
-   [ ] 글쓴이 구별 기능, 댓쓴이 구별기능

### 사용 방법

```sh
$ git clone https://github.com/GGUL-BOB/Backend
$ # .env 파일을 최상단 폴더, 그리고 Django 폴더 하위에 복사
$ cd Backend
$ sudo docker-compose up --build
```

### 기타사항

-   문제 있을시 연락.
