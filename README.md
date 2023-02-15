# PurpleMood_modified

> 개발환경
* OS : windows
* Java : 11
* DB : Oracle
* DBMS : SQLDepveloper
* 서버 실행 : Tomcat8.5
* IDE : VSCode, eclipse
* 배포 : AWS
* 기타환경 : ojdbc6, gson, cos, jstl, JSP, json, jQuery, bootstrap, css, javascript, html, ajax
* 기타 API : 카카오 우편 API, summernote, TMDB
* 기타 협업 툴 : Git, github, source tree, google drive, discord, zoom

<br>
<br>

> 프로젝트 시 활용해본 대표 기술
* Jquery 요소탐색&동적바인딩을 활용한 댓글/신고 기능
* bootstrap, Grid System을 활용한 반응형 웹 구현
* cos, MultipartFormData를 활용한 파일 전송,저장,출력
* StringBuilder를 이용한 페이징, 검색페이징 처리
* front에서 전반적으로 jQuery, 필요시 ajax 사용
* summernote API 사용으로 게시글 작성 구현(이미지 업로드 가능)

<br>
<br>

> 프로젝트 전체 구현 기능
1.	메인 페이지
-	인기 순, 최신 순 콘텐츠 출력
-	OTT 카테고리 버튼 (넷플릭스, 왓챠, 디즈니플러스, 웨이브)
-	검색창
2.	콘텐츠 정보 추출을 위한 TMDB API 사용
3.	검색 기능
-	통합 검색 / OTT별 검색
4.	OTT별 영화 출력 페이지
-	각 OTT에 해당하는 콘텐츠 출력
5.	영화 / 드라마 페이지
-	영화, 드라마 정보 상세 출력
-	해당 OTT 사이트 이동 버튼
6.	로그인
7.	회원가입
-	ajax로 아이디, 닉네임 중복 확인, 결과 출력
-	ajax로 비밀번호 일치 확인, 결과 출력
-	각 항목 유효성 검사
-	카카오 우편 API 사용(우편번호, 주소 직접 입력 불가)
8.	마이페이지
-	회원정보 수정(회원가입과 동일 조건, ID수정 불가)
-	작성한 글 / 댓글 출력
9.	영화/드라마 게시판
-	작성, 출력, 수정, 삭제
-	게시판 리스트 페이징
-	내용 작성 시 Summer note API 사용(이미지 입력, 저장, 출력 구현)
-	카테고리 선택(수정 시 선택된 카테고리 출력)
10.	게시판 댓글 기능(작성 / 출력 / 수정 / 삭제)
11.	게시판 신고 기능
-	다른 사람의 게시글과 댓글 신고
-	본인의 글, 댓글일 경우 신고 태그 출력 X
12.	검색 기능
-	제목/작성자/내용 카테고리 선택 후 검색 가능
-	검색 결과 페이징
13.	관리
-	회원 과 콘텐츠 (드라마, 영화) 전체 출력 및 삭제
-	신고 게시글과 신고 댓글 출력 및 삭제
