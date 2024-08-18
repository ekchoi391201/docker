# Dockerfile
FROM mysql:5.7

# 환경 변수 설정
ENV MYSQL_ROOT_PASSWORD=frodo5020!!
ENV MYSQL_DATABASE=frodo
ENV MYSQL_USER=frodo
ENV MYSQL_PASSWORD=frodo5020!!

# 초기화 스크립트 복사
COPY init.sql /docker-entrypoint-initdb.d/

