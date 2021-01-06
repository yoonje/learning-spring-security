# Spring Framework 정리 자료
처음 배우는 스프링 부트2 웹 부분에 시큐리티 부분을 버그 수정하고 정리한 코드

## Requirements
- [JDK 1.8+](https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
- [gradle](https://gradle.org/)
- [H2](https://www.h2database.com/html/main.html)

**H2 설치 이후 실행하고 application.yml에 맞게 설정해야함**

## Build
```
$ ./gradlew build
```

## Run
```
$ java -jar target/*.jar
```

## 책과 다른 점
- Spring Boot 1.x 버전은 사용하지 않음
- 카카오 인증은 제거
