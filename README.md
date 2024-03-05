# react-ts-registration-form
  회원가입/로그인 페이지 개발

1. Next.js와 TypeScript를 사용한 프로젝트 생성 후 디렉토리로 이동
   $ yarn create next-app --typescript react-ts-registration-form
   $ cd react-ts-registration-form

2. Tailwind CSS 설치(tailwind.config.js와 postcss.config.js 파일을 루트에 생성)
   $ yarn add tailwindcss postcss autoprefixer
   $ npx tailwindcss init -p

3. styles/globals.css 파일에서 Tailwind CSS를 활성화
   @tailwind base;
   @tailwind components;
   @tailwind utilities;

4. 추가로 사용할 패키지 설치(react-hook-form, zod, framer-motion, lucide-react)
   $ yarn add react-hook-form zod framer-motion lucide-react

5. 개발 서버 실행
   $ yarn dev

6. 빌드 및 배포
   $ yarn build
   $ yarn start