# Environment Setup Plan (환경 구축)

## 1. 사용 기술 스택 (Tech Stack)
- **프레임워크**: Next.js 15 (App Router 기반)
- **언어**: TypeScript
- **스타일링**: Tailwind CSS v4, PostCSS
- **컴포넌트/UI**: Radix UI (shadcn/ui 접근 방식 활용)
- **린팅/포맷팅**: ESLint, Prettier

## 2. 초기 셋업 과정
- `npx create-next-app` 을 통해 Next.js 보일러플레이트 생성
- 기존 `Design-QA` 레포지토리와 동일한 수준의 개발 환경 유지를 위해 `tsconfig.json`, `eslint.config.mjs` 적용
- 다크 모드 특화 Tailwind 테마 설정 (`tailwind.config.ts`에 커스텀 색상 매핑)

## 3. 폴더 구조 
```
src/
 ├─ app/          (라우팅 폴더)
 ├─ components/   (재사용 가능한 UI 컴포넌트: 리더보드, 버튼 등)
 ├─ lib/          (유틸리티 함수)
 └─ types/        (TS 타입 정의)
docs/             (기획 및 설계 문서 10종)
```
