```bash
# 프로젝트 생성
docker-compose run --rm composer create-project --prefer-dist laravel/laravel .

# 실행
docker-compose up -d server php mysql

docker-compose up -d --build server

# artisan 실행
docker-compose run --rm artisan migrate

```
