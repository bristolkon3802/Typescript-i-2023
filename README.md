# Typescript 설정

1. nodejs 프로젝트 생성

```
    npm init -y
```

2. typescript 설치

```
    npm install -D typescript
```

3.  touch src/index.ts 파일 생성

4.  touch tsconfig.json 파일 생성
    - 이 파일이 있으면, vscode는 우리가 타입스크립트로 작업한다는 것을 알게 되고, 자동완성 기능을 제공
    - 실행
    - lib : ["ES6","DOM-타겟 런타임 환경"]

```
   npm run build
```

5. 자바스크립트 파일과 모듈을 위한 타입 정의를 작성

6. JSDoc
   코멘트를 제대로 작성하면 타입스크립트가 코멘트를 읽을 수 있음.

# 블록체인 작업증명 Typescript 만들기

0. 프로젝트 생성
   빌드없이 빠르게 새로고침

```
    npm i -D ts-node
```

자동으로 커맨드 재실행

    npm i nodemon

1. 블록체인 디자인

   - crypto 불러오기

   - DefinitelyTyped 리파지토리

   - nodejs에 필요한 타입 전부 설치

```
    npm i -D @types/node
    npm i -D @types/[repositories-name]
```

2. 블록체인 만들기
