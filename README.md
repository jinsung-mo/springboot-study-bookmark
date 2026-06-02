# Spring Boot Bookmark App

> 백엔드 개발 학습 중 처음으로 직접 구현해 본 REST API 프로젝트입니다.

이 프로젝트는 Spring Boot를 활용하여 간단한 북마크(Bookmark) 기능을 제공하는 REST API 서비스입니다. 백엔드 개발의 기초적인 흐름과 RESTful API 설계 및 구현 방법을 학습하기 위해 시작되었습니다.

## 학습 목표
* Spring Boot 프로젝트 기본 구조 이해
* RESTful API의 개념과 HTTP 메서드(GET, POST)의 활용
* `@RestController`, `@RequestMapping`, `@RequestBody` 등 Spring MVC 어노테이션 사용법 익히기
* 클라이언트(웹 브라우저 등)와 서버 간의 JSON 데이터 통신 이해

##  기술 스택
* **Language:** Java
* **Framework:** Spring Boot
* **Build Tool:** Maven

##  API 명세

| HTTP Method | Endpoint | 설명 |
| :---: | :--- | :--- |
| **POST** | `/bookmark` | 새로운 북마크를 등록합니다. JSON 형식으로 데이터를 전송받습니다. |
| **GET** | `/bookmarks` | 저장된 모든 북마크 목록을 조회합니다. |

##  실행 방법

1. 프로젝트를 클론하거나 다운로드합니다.
2. 터미널(또는 명령 프롬프트)에서 프로젝트 루트 디렉토리로 이동합니다.
3. 다음 명령어를 실행하여 애플리케이션을 구동합니다.

```bash
# Windows
mvnw.cmd spring-boot:run

# Mac/Linux
./mvnw spring-boot:run
```

4. 애플리케이션이 실행되면 `http://localhost:8080/bookmarks` 등의 주소로 API를 테스트해 볼 수 있습니다.
