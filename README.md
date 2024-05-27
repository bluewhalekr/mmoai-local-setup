# mmoai-local-setup

mmoai 로컬 셋업

## Instructions
### 1. git clone
```
# docker compose 셋업 repository
git clone git@github.com:bluewhalekr/mmoai-local-setup.git

cd mmoai-local-setup

# gtaas-processing 프로젝트
git clone git@github.com:bluewhalekr/mmoai.git
```

### 2. docker compose로 mmoai 서버 실행
```
# docker compose 실행
docker compose build

docker compose up -d
```

### 3. 사용 후 혹은 로컬 세팅 configuration 업데이트 시
```
docker compose down

## 다시 실행시
docker compose up -d --build
```
