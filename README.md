## Spring Security OAuth Authorization Server

### info
- 기존의 Spring security 그룹에 있던 Oauth2가 지원 종료되었다가 별도의 신규 버전으로 다시 만들어져 샘플 코드 기록용
- 현재는 0.x 버전으로 쓰기 적합한진 모르겠지만 기본 역할은 다 할것 같긴 하다.

### repository
https://mvnrepository.com/artifact/org.springframework.security/spring-security-oauth2-authorization-server

### Relevant information:

This module demonstrates OAuth authorization flow using Spring Authorization Server, Spring OAuth Resource Server and
Spring OAuth Client.

- Run the Authorization Server from the `spring-authorization-server` module
    - IMPORTANT: Modify the `/etc/hosts` file and add the entry `127.0.0.1 auth-server`
- Run the Resource Server from `resource-server` module
- Run the client from `client-server` module
- Go to `http://127.0.0.1:8080/articles`
    - Enter the credentials `admin/password`
- The module uses the new OAuth stack with Java 11

### Relevant Articles:

- [Spring Security OAuth Authorization Server](https://www.baeldung.com/spring-security-oauth-auth-server)
- from: https://github.com/Baeldung/spring-security-oauth/tree/master/oauth-authorization-server
