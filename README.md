# Swagger 스터디

Docker를 사용해서 간단하게 스웨거 페이지 보기.

## Local Env.

1. `git clone ~~~` : 이 레포지토리를 클론한다.
2. `docker compose up -d` : 도커 컨테이너 실행.
   - [docker-compose.yml](docker-compose.yml) : 환경변수의 `SWAGGER_FILE`에 API 문서 경로를 지정.