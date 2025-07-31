## 개발환경 셋팅
1. IntelliJ Community 버전 설치 (2025 버전)
2. mariaDB, Debeaver 설치 및 DB Connection (localhost, 3306)
3. Spring MVC 환경설정 & API Ping
4. datasource & mybatis 연동 (구현 예시와 같은 데이터 DB에 입력)
<br>

## REST API 학습
1. HTTP 통신
<pre>
- HTTP(HyperText Transfer Protocol): 응용 계층의 통신 프로토콜
- 웹 상에서 클라이언트와 서버 간에 데이터(요청/응답)를 주고받는 방식
- 클라이언트가 요청(Request) => 서버가 응답(Response)
</pre>
2. '브라우저 URL 입력 요청 => 서버에서 응답' 하는 과정
<pre>
1) 브라우저에 URL 입력
2) 브라우저가 도메인명으로 IP 주소 조회
  *DNS(Domain Name System): 도메인 -> IP로 바꿔줌
3) 브라우저가 서버와 TCP 연결 시작
  *TCP(Transmission Control Protocol): 전송 계층의 통신 프로토콜
4) 브라우저가 HTTP 요청을 서버로 전송
  *요청라인(GET/POST/PUT/DELETE 등), 요청헤더(클라이언트 정보 등), 요청바디
5) 서버가 요청을 처리하고 응답을 전송
  *상태코드(200, 404 등), 응답헤더(서버 정보, 응답 방식 등), 응답바디(데이터)
6) 브라우저가 데이터 렌더링
</pre>
3. REST API
<pre>
- API(Application Programming Interface): 데이터를 주고받는 방식에 대한 규칙
- REST(Representational State Tranfer): HTTP 메서드, URL 경로 등을 활용하여 데이터를 주고받는 아키텍처 스타일
 
- 클라이언트가 요청(Request) => 서버가 응답(Response)
</pre>
