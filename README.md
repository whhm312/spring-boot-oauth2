# springboot와 oauth2를 활용하여 client 구축
- https://spring.io/guides/tutorials/spring-boot-oauth2 예제 (에러 내용 표시까지)

- /spring-boot-oauth2/src/main/resources/application.yml 에 github와 google client id와 secret 값 추가하기

```yaml
spring:
  security:
    oauth2:
      client:
        registration:
          github:
            clientId: kkk
            clientSecret: ttt
          google:
            client-id: yyy
            client-secret: xxx
```

- github로 로그인 시도 -> 에러처리 예제
- google로 로그인 시도 -> 정상처리 예제
