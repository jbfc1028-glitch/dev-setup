# Docker Nginx 웹서버 실습

## 프로젝트 소개
Docker를 사용해 Nginx 웹서버를 컨테이너화하는 실습입니다.

## 실행 방법

### 1. 이미지 빌드
docker build -t my-web:latest .

### 2. 컨테이너 실행
docker run -d -p 8080:80 my-web:latest

### 3. 접속
브라우저에서 http://localhost:8080 접속

## 실행 결과
![웹페이지 접속 화면](screenshot.png)

## 사용 기술
- Docker
- Nginx
- HTML