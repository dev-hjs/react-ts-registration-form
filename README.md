# react-ts-registration-form
  회원가입/로그인 페이지 개발

1. Next.js와 TypeScript를 사용한 프로젝트 생성 후 디렉토리로 이동
   <pre>
   <code>
   $ yarn create next-app --typescript react-ts-registration-form
   $ cd react-ts-registration-form
   </code>
   </pre>

2. Tailwind CSS 설치(tailwind.config.js와 postcss.config.js 파일을 루트에 생성)
   <pre>
   <code>
   $ yarn add tailwindcss postcss autoprefixer
   $ npx tailwindcss init -p
   </code>
   </pre>
   
3. styles/globals.css 파일에서 Tailwind CSS를 활성화
   <pre>
   <code>
   @tailwind base;
   @tailwind components;
   @tailwind utilities;
   </code>
   </pre>
   
4. 추가로 사용할 패키지 설치(react-hook-form, zod, framer-motion, lucide-react)
   <pre>
   <code>
   $ yarn add react-hook-form zod framer-motion lucide-react
   </code>
   </pre>

5. 개발 서버 실행
   <pre>
   <code>
   $ yarn dev
   </code>
   </pre>

6. 빌드 및 배포
   <pre>
   <code>
   $ yarn build
   $ yarn start
   </code>
   </pre>