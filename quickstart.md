---
layout: default
title: "🚀 빠른 시작"
breadcrumb:
  - name: "빠른 시작"
---

# 🚀 빠른 시작 — AI에게 보내는 명령어 모음

> 어떤 AI 채팅(ChatGPT, Claude, Gemini 등)에서든 아래 명령어를 복사해서 사용하세요.

---

## 📌 기본 사용법

### 방법 1: 전체 프로세스 시작 (승인 게이트 포함)

```
다음 GitHub 레포의 영상 제작 가이드를 읽고 그 방식을 정확히 따라해줘.
모든 규칙(rules.md)을 반드시 지키고, 파이프라인(pipeline.md) 순서대로 진행해.

⚠️ 가장 중요한 규칙:
- 각 단계(STEP 1-A, 1-B, 1-C, 1-D, STEP 2, 3, 4)마다 반드시 내 승인을 받아야 다음으로 넘어갈 수 있어.
- 한 번에 여러 단계를 동시에 출력하지 마.
- 내가 "승인" 또는 "다음"이라고 말하기 전까지 절대 다음 단계로 넘어가지 마.
- STEP 1은 4개 서브 단계(1-A→1-B→1-C→1-D)로 나눠서 하나씩 진행해.

👉 https://github.com/aicatveo3-prog/Auto_Video_Prompt

영상 주제: [여기에 주제 입력]
```

### 방법 2: 특정 단계만 실행

```
다음 GitHub 레포의 영상 제작 가이드를 읽어줘.
👉 https://github.com/aicatveo3-prog/Auto_Video_Prompt

그중에서 STEP [번호]만 실행해줘.
각 단계 끝에 반드시 승인 요청을 해줘. 내 승인 없이 다음으로 넘어가지 마.
[추가 정보/이미지/기획 내용]
```

---

## 🎯 단계별 명령어

### STEP 1: 기획 (서브 단계별)

```
다음 가이드의 STEP 1(기획)을 따라해줘.
👉 https://github.com/aicatveo3-prog/Auto_Video_Prompt/blob/main/prompts/step1-planning.md

⚠️ 중요: STEP 1은 4개 서브 단계(1-A, 1-B, 1-C, 1-D)로 나눠서 진행해.
한 번에 하나만 출력하고, 내 승인을 받아야 다음으로 넘어가.
먼저 STEP 1-A(컨셉 & 캐릭터)부터 시작해.

영상 주제: [여기에 주제 입력]
```

### STEP 2: 이미지 생성 프롬프트

```
STEP 1 기획이 승인 완료되었어. 이제 STEP 2(이미지 생성)를 시작해줘.
👉 https://github.com/aicatveo3-prog/Auto_Video_Prompt/blob/main/prompts/step2-image.md

위 기획을 바탕으로 이미지 프롬프트를 작성하고, 끝에 승인 요청을 해줘.
```

### STEP 3: 이미지 투 비디오 프롬프트

```
STEP 2가 승인 완료되었고 이미지를 생성했어. 이제 STEP 3(비디오 프롬프트)를 시작해줘.
👉 https://github.com/aicatveo3-prog/Auto_Video_Prompt/blob/main/prompts/step3-video.md

첨부한 이미지들을 분석하고 프롬프트를 작성해줘. 끝에 승인 요청도 해줘.
[이미지 첨부]
```

### STEP 4: 음악 생성 프롬프트

```
STEP 3가 승인 완료되었어. 이제 STEP 4(음악 설계)를 시작해줘.
👉 https://github.com/aicatveo3-prog/Auto_Video_Prompt/blob/main/prompts/step4-music.md

위 기획과 장면 구성을 바탕으로 음악을 설계해줘. 끝에 승인 요청도 해줘.
```

---

## 💡 상황별 명령어

### 새 프로젝트 시작할 때

```
다음 가이드를 참고해서 새 영상 프로젝트를 기획해줘.
👉 https://github.com/aicatveo3-prog/Auto_Video_Prompt

주제: "귀여운 고양이 캐릭터의 카페 일상"
스타일: 3D 봉제인형
분위기: 따뜻하고 힐링
```

### 이미지가 이미 있을 때 (STEP 3부터)

```
다음 가이드의 비디오 프롬프트 규칙을 따라해줘.
👉 https://github.com/aicatveo3-prog/Auto_Video_Prompt/blob/main/prompts/step3-video.md
👉 https://github.com/aicatveo3-prog/Auto_Video_Prompt/blob/main/rules.md

규칙 요약:
- 이미지당 3개 프롬프트 (A/B/C)
- "카메라 고정", "이미지 배경 그대로 활용", "음악 없음, 효과음만 있음" 필수
- 마지막에 추천표 + 스토리 흐름 연결

이미지를 첨부할게. [이미지 첨부]
```

### 음악만 필요할 때 (STEP 4만)

```
다음 가이드의 음악 설계 방식을 따라해줘.
👉 https://github.com/aicatveo3-prog/Auto_Video_Prompt/blob/main/prompts/step4-music.md

규칙:
- 영어로 작성 (Suno용)
- Instrumental만
- 프롬프트 + 스타일 태그 모두
- 감정이 확실히 드러나게

내 영상 기획: [기획 내용 붙여넣기]
```

### 예시를 보여주고 싶을 때

```
다음 예시를 참고해서 동일한 형식으로 만들어줘.
👉 https://github.com/aicatveo3-prog/Auto_Video_Prompt/blob/main/examples/festival-project.md
```

---

## ⚡ 초간단 한 줄 명령어

| 목적 | 명령어 |
|------|--------|
| 전체 시작 | "이 가이드 읽고 STEP 1-A부터 시작해. 승인 게이트 꼭 지켜: [URL] / 주제: [주제]" |
| 기획만 | "이 가이드의 STEP 1 따라해. 1-A부터 하나씩: [URL] / 주제: [주제]" |
| 비디오만 | "이 가이드의 STEP 3 따라해. 끝에 승인 요청 해줘: [URL] / 이미지 첨부" |
| 음악만 | "이 가이드의 STEP 4 따라해. 끝에 승인 요청 해줘: [URL] / 기획: [내용]" |
| 예시 참고 | "이 예시랑 같은 형식으로: [예시 URL]" |

---

## 🔒 승인 게이트 진행 흐름

```
사용자: 주제 입력
  ↓
AI: STEP 1-A 출력 + 🔒 승인 요청
사용자: "승인" (또는 수정 요청)
  ↓
AI: STEP 1-B 출력 + 🔒 승인 요청
사용자: "승인"
  ↓
AI: STEP 1-C 출력 + 🔒 승인 요청
사용자: "승인"
  ↓
AI: STEP 1-D 출력 + 🔒 승인 요청
사용자: "승인"
  ↓
AI: "STEP 1 완료! STEP 2를 시작하려면 말씀해주세요."
사용자: "STEP 2 시작해"
  ↓
AI: STEP 2 출력 + 🔒 승인 요청
사용자: "승인" → 이미지 생성 → "STEP 3 시작해" + 이미지 첨부
  ↓
AI: STEP 3 출력 + 🔒 승인 요청
사용자: "승인" → "STEP 4 시작해"
  ↓
AI: STEP 4 출력 + 🔒 승인 요청
사용자: "승인"
  ↓
🎉 전체 완료!
```

---

## 🔗 주요 URL 모음

| 문서 | URL |
|------|-----|
| 전체 가이드 (홈) | `https://github.com/aicatveo3-prog/Auto_Video_Prompt` |
| 파이프라인 | `.../blob/main/pipeline.md` |
| 공통 규칙 | `.../blob/main/rules.md` |
| STEP 1 프롬프트 | `.../blob/main/prompts/step1-planning.md` |
| STEP 2 프롬프트 | `.../blob/main/prompts/step2-image.md` |
| STEP 3 프롬프트 | `.../blob/main/prompts/step3-video.md` |
| STEP 4 프롬프트 | `.../blob/main/prompts/step4-music.md` |
| 축제 프로젝트 사례 | `.../blob/main/examples/festival-project.md` |
| 기획서 예시 | `.../blob/main/examples/planning-example.md` |
| 비디오 프롬프트 예시 | `.../blob/main/examples/video-prompts-example.md` |
| 음악 프롬프트 예시 | `.../blob/main/examples/music-prompts-example.md` |

---

## ⚠️ 주의사항

1. **승인 게이트가 가장 중요** — AI가 승인 없이 다음으로 넘어가면 "멈춰. 승인 안 했어."라고 말하세요
2. **AI가 URL을 읽을 수 있는지 확인** — 일부 AI는 URL 직접 접근이 안 될 수 있음
3. URL이 안 될 경우 → 해당 문서의 **내용을 복사해서 직접 붙여넣기**
4. **이미지 첨부는 STEP 3에서만** 필요
5. 같은 대화에서 STEP 1→2→3→4 순서로 하면 **맥락이 이어져서 가장 좋음**
6. 다른 채팅으로 넘어갈 때는 **이전 단계 결과물을 함께 복사**
7. **수정은 몇 번이든 가능** — 마음에 들 때까지 수정 요청하세요
