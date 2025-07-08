# kafka-react-vite-app
kafka 연결을 위한 vite react app 보일러 플레이트 저장소 입니다.

# 사전 준비
- docker: v28.x ('25.7.7 기준 lts)
- node: v22.x ('25.7.8 기준 lts)

# 사용법

## 실행

```
bash ./scripts/docker-run.sh <DOCKER HUB ID>
```
- 위 명령어 사용시 `app 빌드 -> docker 빌드 -> docker push -> docker run` 순서로 진행됩니다.

## 테스트

- `npm run dev` 혹은 `yarn dev` 를 통해 개발용으로 열 수 있습니다.
