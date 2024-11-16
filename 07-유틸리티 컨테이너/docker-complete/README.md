유틸리티 컨테이너를 사용하여 로컬 환경에 node를 설치하지 않고 npm 명령어를 사용할 수 있다

```bash
# 실행 후 컨테이너 삭제
docker-compose run --rm npm init
docker-compose run --rm npm install

# 중단된 컨테이너 삭제
docker container prune
```
