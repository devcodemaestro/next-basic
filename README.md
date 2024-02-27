# yarn 설치 및 활용

- npm 대비 안정적이고 속도가 빠르다.
- `npm install -g yarn`
- `yarn --version`
- `yarn add 패키지명`
- `yarn install` : node_modules 를 설치

# Next.js

- [Next.js](https://nextjs.org)
- [DOC](https://nextjs.org/docs)

## 1. 프로젝트 생성

- `npx create-next-app`
- `npx create-next-app@latest` (최신버전 14버전)
- Yes : typeScript, /scr, App router, EXLint
- No : TailWind, alias

## 2. 프로젝트 실행

- yarn dev 또는 npm dev
- localhost:3000 실행
- 참고로 SSR 방식 (서버가 있어야 한다.)
  : Server Side Rendering
  : JS 가 동작하지 않아도 화면은 출력(HTML/CSS)
- 참고로 CSR 방식
  : Client Side Rendering (React)
  : JS 가 동작하지 않으면 화면도 출력 안됨(HTML/CSS)
