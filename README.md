# ganggyunggyu

TypeScript, React, Next.js, FastAPI, Python

AI 서비스, 자동화 봇, 게임, IoT까지 — 아이디어가 떠오르면 직접 만들어보고 있습니다.

---

## Tech Stack

### Frontend
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![Vue](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vue.js&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=flat-square&logo=framer&logoColor=white)

### Backend & Infra
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)

### State Management & Data
![Jotai](https://img.shields.io/badge/Jotai-000000?style=flat-square&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-443E38?style=flat-square&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)

### Others
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00878F?style=flat-square&logo=arduino&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

---

## Projects

### AI & LLM Services

| Project | Description | Stack |
|---------|-------------|-------|
| **21lab** | 블로그 검색 키워드 관리 및 노출 현황을 추적하는 실시간 대시보드. 스프레드시트 기반 데이터 편집, Prisma ORM 연동 | Next.js 15, Prisma, Tailwind CSS, Jotai |
| [**gng**](https://github.com/ganggyunggyu/gng) | OpenAI, Anthropic, Gemini, xAI, DeepSeek, Solar 등 멀티 프로바이더 AI 채팅 워크벤치. 프로젝트별 시스템 프롬프트 관리, 이미지 생성, IndexedDB 로컬 저장, SSE 스트리밍 | Next.js 16, Jotai, Dexie, Radix UI |
| **ashrealm** | d20 기반 다크 판타지 AI TRPG. AI 던전 마스터(Function Calling), pgvector 벡터 검색 로어북, WebSocket 실시간 멀티플레이 | Next.js 15, FastAPI, PostgreSQL, pgvector, Shadcn/ui |
| **real-time-sdk** | OpenAI Realtime API(WebRTC) 기반 실시간 양방향 음성/텍스트 에이전트 콘솔 | Next.js 16, @openai/agents, TanStack Query, Jotai |
| [**local-image-hub**](https://github.com/ganggyunggyu/local-image-hub) | NovelAI API 연동 로컬 이미지 생성 서비스. NAI v3/v4 모델 지원, 비동기 생성, Base64/ZIP 응답 | FastAPI, httpx, Python 3.12 |

### Automation & Bots

| Project | Description | Stack |
|---------|-------------|-------|
| [**blog-cron-bot**](https://github.com/ganggyunggyu/blog-cron-bot) | 네이버 블로그 노출 모니터링 봇. 키워드 기반 랭킹 추적, 인기글/스마트블로그 분류, Socket.io 실시간 대시보드, node-cron 스케줄링 | TypeScript, Express, Playwright, Cheerio, Mongoose, Socket.io |
| [**cafe-bot**](https://github.com/ganggyunggyu/cafe-bot) | 네이버 카페 자동 게시물/댓글 작성 봇. BullMQ 잡 큐, Bull Board 모니터링 대시보드, 멀티 계정 관리 | Next.js 16, Playwright, BullMQ, Redis, Mongoose |
| **x-bot** | X(Twitter) 게시물 예약 발행 및 미디어 관리 봇. BullMQ 스케줄링, OAuth 2.0 인증 | Next.js 16, BullMQ, twitter-api-v2, Mongoose, Playwright |
| **mersoom-bot** | 머슴 커뮤니티 자동 활동 봇. PoW(SHA256) 인증, 게시글/댓글/투표 자동화, JSON 기반 상태 관리 | Python, SHA256, REST API |

### Game Development

| Project | Description | Stack |
|---------|-------------|-------|
| **retro-beats** | 유튜브 음악으로 실시간 비트맵을 생성하여 플레이하는 웹 리듬 게임. Tone.js 오디오 분석, 레트로 아케이드 UI | Next.js 15, Tone.js, Framer Motion, Jotai, react-youtube |

### Web Applications

| Project | Description | Stack |
|---------|-------------|-------|
| [**naver-search-app**](https://github.com/ganggyunggyu/naver-search-app) | 네이버 검색 결과 크롤링 및 블로그 인기글 추출 도구. Cheerio 기반 HTML 파싱, 동적 CSS 셀렉터 폴백 | React Router 7, Vite, Cheerio, Jotai, got-scraping |
| **google-docs-api** | Google Docs OAuth 2.0 연동 문서 편집기. CRUD, Google Drive 동기화, 실시간 문서 검색 | Next.js 14, NextAuth, googleapis, TanStack Query, Jotai |
| **google-sheet-test** | Google Sheets API 연동 데이터 관리 대시보드. 인라인 편집, 날짜 기반 필터링, MongoDB Upsert 패턴 | Next.js 16, googleapis, Mongoose, TanStack Query, Jotai |
| [**my-blog**](https://github.com/ganggyunggyu/my-blog) | 개인 개발 블로그. MDX 기반 포스트, PrismJS 코드 하이라이팅, Monaco Editor 통합, 테마 지원 | Next.js 15, MDX, next-mdx-remote, Jotai |
| **blog-memo** | 공개 키워드 메모 서비스. 키워드 태깅, 지표 파싱, 타이틀 버전 히스토리 | Next.js 15, Tailwind CSS, TypeScript |
| [**life-calendar**](https://github.com/ganggyunggyu/life-calendar) | 10년/1년/월/주/일 단위로 줌인/줌아웃하며 보는 인생 타임라인 캘린더. PWA 오프라인 지원 | Next.js 16, Framer Motion, Jotai, TanStack Query, next-pwa |
| [**nalgeu**](https://github.com/ganggyunggyu/nalgeu) | 감정 기반 아날로그 음악 공유 서비스. 감정 로깅, 음악 추천, 아날로그 플레이어 UI | Next.js 16, Supabase, Framer Motion, TanStack Query, Jotai |
| **band-test** | 밴드 멤버 매칭 서비스. 스와이프 매칭, Supabase 실시간 채팅 | Next.js 16, Supabase, Zustand, TanStack Query, Zod |
| **past-life-quiz** | 전생 직업/성격 진단 심리 테스트. 결과 이미지 공유(html2canvas), 애니메이션 | React 19, Framer Motion, html2canvas, Jotai |
| [**jp-typing**](https://github.com/ganggyunggyu/jp-typing) | 로마자 입력 기반 일본어 타자 연습 도구. 문장/노래 모드, 실시간 피드백, 통계 추적 | Next.js 16, Tailwind CSS, TypeScript |
| **temp-cal** | 멀티스케일 타임라인 캘린더(10Y/1Y/1M/1W/1D). 모바일 최적화 | Next.js 15, date-fns, Jotai |

### IoT & Hardware

| Project | Description | Stack |
|---------|-------------|-------|
| **culture-con** | 포토카드 판매 키오스크 시스템. ESP32 릴레이 제어, Web Bluetooth 통신, 바코드 스캐너, 쿠폰 검증, 키오스크 터치 잠금 모드 | Next.js 16, Vite, ESP32/Arduino, Web Bluetooth API, Mongoose |

### Desktop & Mobile

| Project | Description | Stack |
|---------|-------------|-------|
| [**image-setakgi-py-app**](https://github.com/ganggyunggyu/image-setakgi-py-app) | 이미지 메타데이터 제거 및 자유 변형 데스크톱 앱. 드래그앤드롭, 실시간 프리뷰, EXIF 편집, 1px 정밀 조정 | Python, PySide6, OpenCV, Pillow, piexif, PyInstaller |
| **ios-app-test** | MVVM + Clean Architecture iOS 앱. Alamofire 네트워킹, Kingfisher 이미지 캐싱, SnapKit 레이아웃, KeychainAccess | Swift 5.5+, iOS 15+, SPM |

### Image Processing & Generation

| Project | Description | Stack |
|---------|-------------|-------|
| [**image-batch-gen**](https://github.com/ganggyunggyu/image-batch-gen) | Google Gemini API 기반 대량 이미지 생성 CLI. 다중 모델 지원, 프롬프트 버전 관리, 종횡비 설정 | TypeScript, @google/genai, Sharp |
| **image-setakgi-api** | 랜덤 이미지 변환 API. 배치 처리, Base64 핸들링, CORS 지원 | FastAPI, Pillow, numpy |

### Libraries & Tools

| Project | Description | Stack |
|---------|-------------|-------|
| **ggg ([@ganggyunggyu/shared](https://www.npmjs.com/package/@ganggyunggyu/shared))** | 공유 상수/타입/유틸리티 monorepo 패키지. CJS/ESM 듀얼 빌드 | TypeScript, pnpm workspace, tsup, Vite |
| **export-mongo-db** | MongoDB 전체 컬렉션 CSV/JSON 내보내기 도구. ObjectId/DateTime/Decimal128 자동 변환 | Python, PyMongo |
| **projects/code-judge-platform** | 웹 코딩 테스트 플랫폼 MVP. Monaco Editor, SSE 실시간 업데이트, Docker 배포 | Next.js 15, Monaco Editor, Docker |
| **port-checker** | 포트 사용 여부 확인 유틸리티 | Next.js 15 |

---

## Architecture

대부분의 프로젝트에 **FSD(Feature-Sliced Design)** 아키텍처를 적용하고 있습니다.

```
src/
├── app/        # 앱 진입점, 라우팅
├── pages/      # 페이지 컴포넌트
├── widgets/    # 독립적 UI 블록
├── features/   # 사용자 시나리오, 비즈니스 로직
├── entities/   # 도메인 모델
└── shared/     # 공용 유틸, 타입, UI, config
```

**상태 관리**: Jotai(클라이언트) + TanStack Query(서버)
**폼 처리**: React Hook Form + Zod
**스타일링**: Tailwind CSS

---

## GitHub Stats

![ganggyunggyu's GitHub stats](https://github-readme-stats.vercel.app/api?username=ganggyunggyu&show_icons=true&theme=tokyonight&hide_border=true)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=ganggyunggyu&layout=compact&theme=tokyonight&hide_border=true)
