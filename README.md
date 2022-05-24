# 금융결제원 오픈뱅킹 API를 사용한 Web Application 프로젝트
## 사양
- Java 8
- IntelliJ
- Tomcat
- Postman

## Open API
- **금융결제원 오픈뱅킹 API**
  - https://developers.kftc.or.kr
  - 잔액조회, 거래내역조회, 계좌실명조회, 입금이체

## 순서
| |내용|branch|
|--|--|--|
|1|Servlet MVC - GET, 잔액조회|servlet-mvc-get|
|2|Servlet MVC - 입력값에 따라 응답 데이터 분기|response-by-parameter|
|3|Servlet MVC - 파일의 데이터 응답|file-response-data|
|4|Servlet MVC - JSON 데이터 응답|json-response|
|5|Servlet MVC - POST, 계좌실명조회|json-request|
|6|Servlet과 Controller 분리|servlet-and-controller|
|7|Dispatcher Servlet|dispatcher-servlet|
|8|거래내역조회|transaction-list|
|9|입금이체|deposit-transfer|
|10|File Data Controller|file-data-controller|
