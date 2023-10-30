## 환경

- Node.js: 16.14.0
- Next.js: 12.2.3
- React: 18.2.0

## 설치

```bash
npm install
```

## 개발 서버 기동

```
npm run dev
```

http://localhost:3000/ 접속

## Storybook 기동

```
npm run storybook
```

http://localhost:6006/ 접속

## 테스트 실행

단위 테스트 실행

```
npm run test
```

## 소스 코드 린터/포매터

소스 코드를 린터로 확인

```
npm run lint
```

소스 코드를 포매터로 정리

```
npm run format
```

## 패키지 구성

```
├── .editorconfig
├── .env  <-- 환경 변수
├── .env.production  <-- 프러덕션용 환경 변수
├── .eslintrc.json  <-- ESLint 설정 파일
├── README.md
├── jest.config.js  <-- Jest 설정 파일
├── jest.setup.js  <-- 테스트 파일이 실행되기 전에 실행된다
├── next-env.d.ts
├── next.config.js  <-- Next.js 설정 파일
├── package-lock.json
├── package.json
├── public
├── src
│   ├── components  <-- Presentational Components
│   ├── containers  <-- Container Compoments
│   ├── contexts  <-- React Context
│   ├── pages  <-- Next.js 페이지
│   ├── services  <-- Web API Client
│   ├── themes  <-- styled-components 테마
│   ├── types  <-- 타입 정의
│   └── utils  <-- 범용 함수
└── tsconfig.json
```
