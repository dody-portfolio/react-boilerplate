# 리액트 보일러플레이트

## idea

- yarn berry 도입할것

## 업데이트 로그

### 2024/07/14

- cra로 nextjs 프로젝트 설정

- 폰트 설정

  - pretendard 설정 (로컬로 폰트 가져와서, customFont Provider만들어서 layout에서 불러오기)

- 상태관리 라이브러리 가장 심플한걸로

  - zustand

- css / 스타일링 라이브러리

  - tailwindcss
    - globals.css에 tailwind Unknown 에러 있는거 수정 - tailwind를 인식하지 못해서 발생하는 에러인데, 코드편집기에서 인식 해서발생하는 경우도 있어서 extension을 설치해주면 된다 - vsc 'PostCSS Language Support' extension install
  - scss 패키지 설치

- meta data provider

- cra로 만들어진 리액트도 내장된 컴파일러를 사용하는데,
  nextjs의 경우에는 바벨을 사용한다.
  https://react.dev/learn/react-compiler#usage-with-nextjs
