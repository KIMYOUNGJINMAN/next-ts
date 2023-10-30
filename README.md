## Use Case
   ![유스케이스](https://github.com/KIMYOUNGJINMAN/next-ts/assets/149396100/83fa2a31-09fd-41a2-8932-6ceea9c80aed)
        
    | 유스케이스 | 상세 | 관련 페이지 |
    | --- | --- | --- |
    | 상품을 검색 | 상품 목록을 표시 | 첫 페이지, 검색 페이지, 상품 상페 페이지 |
    | 상품을 구입 | 상품을 장바구니에 넣고, 구입 | 장바구니 페이지 |
    | 상품을 등록 | 필요한 정보를 입력하고, 상품을 게시 | 상품 등록 페이지 |
    | 판매자 프로파일 표시 | 판매자 프로파일 표시, 판매자 상품목록 표시 | 사용자 페이지 |
    | 로그인 | 시스템 로그인 | 로그인 페이지 |
        
## 아키텍처
![아키텍처](https://github.com/KIMYOUNGJINMAN/next-ts/assets/149396100/eb292c31-8bfa-41fd-ac07-1b0b7c69c0c1)

## 환경

- Node.js: 16.14.0
- Next.js: 12.2.3
- React: 18.2.0
- typescript: 4.6.2
- ESLint/Pretter/StoryBook

## 설치

```bash
npm install
```

## 개발 서버 기동

```
npm run dev
```

## Storybook 기동

```
npm run storybook /* port: 6006 */
```

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
