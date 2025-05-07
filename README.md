# 반찬 쇼핑몰 프로젝트

Spring Boot + JSP + MyBatis 기반의 반응형 반찬 쇼핑몰 웹 애플리케이션입니다.

# 사용 기술
- 백엔드: Spring Boot, MyBatis, JSP
- 프론트엔드: Bootstrap, jQuery, JavaScript
- DB: MariaDB
- 빌드 도구: Gradle
- 기타: Git, DevTools, JSTL

# 주요 기능
- 회원가입 / 로그인 / 로그아웃
- 상품 목록 / 상세 조회
- 장바구니 / 주문 처리
- 관리자 상품 관리 (등록, 수정, 삭제)
- 마이페이지: 주문 내역 조회

# 프로젝트 구조
src
  - controller
  - model
  - mapper
  - service
  - views


# 개발 환경
- Java 17
- Spring Boot 3.4.5
- Eclipse 또는 IntelliJ
- 포트: `8082`

# 실행 방법
```bash
# 프로젝트 실행
./gradlew bootRun
