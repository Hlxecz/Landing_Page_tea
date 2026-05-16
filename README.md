# 🍵 ASSAM TEA

> ElevenLabs를 활용한 이미지·영상 제작 및 프롬프트 엔지니어링 학습 프로젝트

## 📋 소개

**ASSAM TEA**는 ElevenLabs AI를 활용하여 이미지와 영상을 제작하고, 프롬프트 엔지니어링을 학습한 결과물을 시네마틱 스크롤 기반 랜딩 페이지로 구현한 프로젝트입니다.

스크롤에 따라 영상이 프레임 단위로 재생되며, Apple 스타일의 몰입감 있는 브랜드 스토리텔링 경험을 제공합니다.

## 🎬 Preview

<video src="tea-story-fianl.mp4" controls width="100%"></video>

## ✨ 주요 기능

- **스크롤 기반 영상 재생** — 150 프레임 Canvas 렌더링, 4개 병렬 워커로 고속 로딩
- **GSAP ScrollTrigger** — 텍스트 오버레이 페이드 인/아웃, 카드 애니메이션
- **시네마틱 로딩 화면** — 실시간 프레임 추출 진행률 표시
- **프리미엄 UI** — 다크 테마, Cormorant Garamond 타이포그래피, 앰버 컬러 시스템

## 🛠 기술 스택

| 분류 | 기술 |
|---|---|
| **AI 영상 제작** | ElevenLabs |
| **Frontend** | HTML, CSS, JavaScript |
| **애니메이션** | GSAP, ScrollTrigger |
| **렌더링** | Canvas API, ImageBitmap |
| **서버** | Node.js, Express |

## 🚀 실행 방법

```bash
npm install
npm run start
```

→ http://localhost:3000 접속

## 📝 학습 내용

- ElevenLabs를 활용한 AI 이미지 및 영상 생성
- 효과적인 프롬프트 작성법 및 엔지니어링 기법
- 스크롤 기반 비디오 프레임 추출 및 Canvas 렌더링
- 병렬 처리를 통한 프레임 로딩 성능 최적화
