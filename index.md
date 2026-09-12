---
layout: default
title: "🎬 Auto Video Prompt"
---

# 🎬 Auto Video Prompt

### AI 영상 제작 파이프라인 가이드 — 기획부터 음악까지

> **어떤 AI 채팅에서든, 이 가이드 URL 하나만 던져주면 동일한 품질의 영상 제작 프로세스를 실행할 수 있습니다.**

---

## 🎯 이 사이트는 무엇인가요?

AI 도구들(ChatGPT, Claude, Gemini 등)이 **영상 제작 전 과정**을 체계적으로 도와줄 수 있도록 만든 **표준 제작 가이드**입니다.

```
AI 이미지 생성 → 이미지 투 비디오(I2V) → AI 음악 생성 → 편집
```

---

## 🔄 4단계 파이프라인

| STEP | 단계 | 입력 | 출력 |
|------|------|------|------|
| **1** | [🎬 기획](prompts/step1-planning) | 영상 주제/컨셉 | 스토리, 캐릭터, 감정선, 이미지 목록 |
| **2** | [🖼️ 이미지 생성](prompts/step2-image) | 기획서 | 장면별 AI 이미지 프롬프트 |
| **3** | [🎥 이미지→비디오](prompts/step3-video) | 생성된 이미지 | 이미지당 3개(A/B/C) 비디오 프롬프트 |
| **4** | [🎵 음악 생성](prompts/step4-music) | 기획 + 장면 구성 | Suno 영어 프롬프트 + 스타일 태그 |

> 📖 상세 프로세스: [파이프라인 전체 보기](pipeline)

---

## 🚀 빠른 시작

AI에게 이렇게 말하세요:

```
다음 GitHub 레포의 영상 제작 가이드를 읽고 그 방식을 정확히 따라해.
내가 영상 주제를 알려줄 테니 STEP 1(기획)부터 시작해.
👉 https://github.com/aicatveo3-prog/Auto_Video_Prompt
```

> 🚀 더 많은 명령어: [빠른 시작 가이드](quickstart)

---

## 📂 사이트 구조

| 문서 | 설명 |
|------|------|
| [🔄 파이프라인](pipeline) | 전체 제작 프로세스 상세 |
| [📏 공통 규칙](rules) | 모든 프롬프트에 적용되는 규칙 |
| [🚀 빠른 시작](quickstart) | AI에게 보내는 명령어 모음 |
| **📝 프롬프트** | |
| ∟ [STEP 1: 기획](prompts/step1-planning) | 영상 기획 프롬프트 |
| ∟ [STEP 2: 이미지](prompts/step2-image) | 이미지 생성 프롬프트 |
| ∟ [STEP 3: 비디오](prompts/step3-video) | 이미지→비디오 프롬프트 |
| ∟ [STEP 4: 음악](prompts/step4-music) | 음악 생성 프롬프트 |
| **💡 실제 사례** | |
| ∟ [축제 프로젝트 전체](examples/festival-project) | 파발이×영꾸꾸 축제 애니메이션 |
| ∟ [기획서 예시](examples/planning-example) | STEP 1 결과물 예시 |
| ∟ [비디오 프롬프트 예시](examples/video-prompts-example) | STEP 3 결과물 예시 |
| ∟ [음악 프롬프트 예시](examples/music-prompts-example) | STEP 4 결과물 예시 |

---

## 📏 핵심 규칙 요약

- ✅ **비디오 프롬프트**: 카메라 고정 / 배경 유지 / 음악 없음, 효과음만
- ✅ **이미지당 프롬프트**: 최소 3개 (A: 기본, B: 감정 강화, C: 변형)
- ✅ **음악 프롬프트**: 영어 / Instrumental / 프롬프트 + 스타일 태그
- ✅ **출력 형식**: 마크다운 표 + 코드블록 + 추천표 + 흐름 연결

> 📏 상세 규칙: [공통 규칙 전체 보기](rules)

---

## 💡 실제 사례

이 가이드로 제작한 첫 프로젝트:

### 🎪 파발이 × 영꾸꾸 축제 애니메이션

- 3D 봉제인형 스타일 캐릭터
- 축제장 배경 13파트 스토리
- 이미지 13장 → 비디오 프롬프트 39개 → 음악 10곡

> 💡 [전체 사례 보기](examples/festival-project)

---

**Made with ❤️ for AI-powered video production**
