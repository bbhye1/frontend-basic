# 개발 환경

리액트 등 스더라도 개발 환경은 풀체인이라 부르는 노드제이에스를 쓴다.

Deno 등도 있다 (간단)
하지만 아직까지 보통 node를 씀.

프론트엔드 도구들은 계속 바뀐다.
그래서 이래서 이건 쓰는구나를 이해해서 바뀌는 환경들이 왜 바뀌는지 이해하고 적용하는 데 도움이 됨.

- [나의 최신 버전 세팅](내꺼 링크 달기)

node 세팅 전 해야할 일

1. 버젼을 먼저 확인해야 한다.
2. fnm 설치 확인하고 node 버전을 설정한다.

## NPM(Node Package Manager)

> 노드 패키지를 관리하는 매니저

### 명령어

- npx -
- -D (--save-dev): 개발 도구로서 설치하는 패키지들
  - 배포할 때는 올라가지 않기 때문에 배포하는 크기를 줄일 수 있고 
  - 배포할 때는 올라가지 않기 때문에 악의적 공격에 의해 실행되지 않음.








---

- Node.js
- NPM(Node Package Manager)
  - package.json / package-lock.json
  - node_modules
  - npx
- ES Modules vs CommonJS