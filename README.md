# 원그라운드 (One Ground) — 브랜드 랜딩 페이지

무인 공간 AI CRM SaaS **스페이스데스크** 소개 및 리드 수집을 위한 브랜드 랜딩 페이지

---

## 프로젝트 소개

원그라운드의 메인 프로덕트 **스페이스데스크**를 소개하는 싱글 페이지 랜딩 사이트입니다.  
파티룸·스터디카페·무인카페 운영자를 타겟으로, 무료 상담 신청 리드를 수집합니다.

---

## 페이지 구성

| 섹션 | 설명 |
|------|------|
| Hero | 메인 카피 + CTA 버튼 + 핵심 지표 (문의 자동화율, 수강생 수) |
| BusinessPillars | 스페이스데스크 4대 핵심 기능 소개 |
| CaseStudies | 실제 운영 사례 — 도입 전·후 비교 |
| Impact | 수치로 보는 도입 효과 |
| Partners | 강의 이력 및 파트너 기관 |
| Contact | 무료 상담 신청 폼 |

---

## 기술 스택

| 기술 | 버전 |
|------|------|
| Astro | 6.0 |
| Tailwind CSS | 4.2 |
| Node.js | 22.12+ |

- SEO: Open Graph, Twitter Card, JSON-LD Schema (Organization, SoftwareApplication)
- 배포: Vercel / Netlify

---

## 시작하기

```bash
# 의존성 설치
npm install

# 개발 서버 실행 (localhost:4321)
npm run dev

# 프로덕션 빌드
npm run build

# 빌드 결과 미리보기
npm run preview
```

---

## 프로젝트 구조

```
oneground/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   ├── Navbar.astro
│   │   ├── Hero.astro
│   │   ├── BusinessPillars.astro
│   │   ├── CaseStudies.astro
│   │   ├── Impact.astro
│   │   ├── Partners.astro
│   │   ├── Contact.astro
│   │   └── Footer.astro
│   ├── layouts/
│   │   └── Layout.astro       # 공통 레이아웃 + SEO 메타태그 + JSON-LD
│   ├── pages/
│   │   └── index.astro
│   └── styles/
│       └── global.css
├── astro.config.mjs
└── package.json
```
