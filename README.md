# azle-simple-game

## Installation

1. [azle-simple-game 레포지토리](https://github.com/maemil/azle-simple-game)를 자신의 계정으로 fork 합니다.

2. 터미널에서 프로젝트 폴더를 생성하길 원하는 위치로 이동한 후, 다음과 같이 입력합니다.

```
git clone https://github.com/자신의_계정_아이디/azle-simple-game
```

3. 자신의 깃허브 레포지토리가 성공적으로 로컬에 fork 되었다면, 아래와 같이 입력합니다.

```
dfx start --background --clean
cd azle-simple-game/simple_game
npm install
npm run canister_deploy_local
```

정상적으로 `simple_game` 캐니스터가 배포되었는지 확인합니다.

4. `token` 캐니스터도 동일하게 배포합니다.

```
cd ../token
npm install
npm run canister_deploy_local
```

`token` 캐니스터도 정상적으로 배포되었는지 확인합니다.
