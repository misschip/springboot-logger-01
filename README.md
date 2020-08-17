# AOP와 BindResult를 이용한 로그 파일 만들기

## 로그 레벨
- 로그는 해당 level 위로는 다 기록된다. 예를 들어 info level이면 info, warn, error
- debug -> info -> warn -> error

## 참고 주소
- http://logback.qos.ch/manual/
- https://blog.naver.com/getinthere/221799123006

## 의존성
```xml
<dependency>
	<groupId>org.springframework.boot</groupId>
	<artifactId>spring-boot-starter-aop</artifactId>
</dependency>

<dependency>
	<groupId>org.springframework.boot</groupId>
	<artifactId>spring-boot-starter-validation</artifactId>
</dependency>
<dependency>
	<groupId>org.springframework.boot</groupId>
	<artifactId>spring-boot-starter-web</artifactId>
</dependency>
```