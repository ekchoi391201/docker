# 베이스 이미지로 최신 Redis 이미지를 사용합니다
FROM redis:latest

# 커스텀 Redis 설정 파일을 컨테이너의 /usr/local/etc/redis/ 디렉토리에 복사합니다
COPY redis.conf /usr/local/etc/redis/redis.conf

# 커스텀 설정 파일을 사용하여 Redis 서버를 시작합니다
CMD ["redis-server", "/usr/local/etc/redis/redis.conf"]

