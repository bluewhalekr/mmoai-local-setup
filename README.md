# mmoai-local-setup

mmoai 로컬 셋업

## Requirements (Mac 기준)
> Docker Desktop (상황에 따라 설정에서 Resources 증가)

## Instructions
### 1. git clone
```
# docker compose 셋업 repository
git clone git@github.com:bluewhalekr/mmoai-local-setup.git

cd mmoai-local-setup

# gtaas-processing 프로젝트
git clone git@github.com:bluewhalekr/mmoai.git
```

### 2. docker compose로 프로젝트 환경 실행
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