# 🎬 YouTube Content Generation Prompt Package

> 대규모 언어 모델(LLM)을 활용하여 유튜브 콘텐츠 기획, 대본 작성, 썸네일 문구 및 제목 추천 과정을 자동화하기 위한 Prompt Engineering 프로젝트입니다.

---

# 📌 프로젝트 목표

본 프로젝트는 LLM을 이용하여 유튜브 콘텐츠 제작 과정을 자동화하는 것을 목표로 합니다.

사용자가 영상 주제만 입력하면 아래 과정을 자동 수행합니다.

- 영상 아이디어 기획
- 대본 생성
- 제목 추천
- 썸네일 문구 생성
- SEO 키워드 반영

---

# 👥 대상 사용자

- 유튜브 채널 운영자
- 콘텐츠 제작자
- AI Prompt Engineer
- 마케팅 담당자

---

# 📂 프로젝트 구성

```
youtube-llm-prompt

├── README.md
├── docs
│   ├── 01_model_comparison.md
│   ├── 02_system_design.md
│   ├── 03_few_shot_examples.md
│   ├── 04_hallucination_validation.md
│   ├── 05_conversation_log.md
│   ├── 06_prompt_versions.md
│   ├── 07_operation_policy.md
│   └── 08_cost_optimization.md
│
├── prompts
│   ├── system_prompt.md
│   ├── planning_prompt.md
│   ├── script_prompt.md
│   └── thumbnail_prompt.md
│
└── examples
    ├── sample_input.md
    ├── sample_output.md
    └── evaluation_result.md
```

---

# 🎯 프로젝트 기능

## 1. 영상 기획

- 키워드 분석
- 타겟 시청자 분석
- 영상 구성 추천

---

## 2. 대본 생성

- Hook 작성
- 본문 구성
- CTA(Call To Action) 생성

---

## 3. 제목 생성

CTR(클릭률)을 고려한 제목 자동 생성

예시

- AI가 대신 돈 벌어드립니다
- ChatGPT로 월 100만원 버는 방법

---

## 4. 썸네일 문구 생성

예시

- 진짜 됩니다
- 90%가 모릅니다
- 이거 하나면 끝

---

# 🤖 비교한 LLM 모델

|Model|용도|
|------|------|
|GPT-4o|정확한 지시 수행|
|Claude 3.5 Sonnet|최종 대본 생성|
|Gemini 1.5 Pro|브레인스토밍 및 아이디어|

---

# 📑 문서

|문서|설명|
|-----|------|
|01|모델 비교|
|02|시스템 설계|
|03|Few-shot 예시|
|04|환각 검증|
|05|10Turn 대화|
|06|Prompt 개선|
|07|운영 정책|
|08|비용 절감 전략|

---

# 💰 비용 절감 전략

- Gemini를 활용한 초안 생성
- Claude를 이용한 최종 대본 작성
- Context Compression으로 토큰 절감
- Prompt 분리를 통한 재사용

---

# 🛡 Hallucination 대응

사실 정보는 반드시 근거 기반으로 작성한다.

근거가 없는 경우

> **[확인 필요]**

라고 출력하도록 설계하였다.

---

# 📌 최종 선정 모델

**Claude 3.5 Sonnet**

선정 이유

- 긴 문맥 유지 능력 우수
- 자연스러운 한국어 표현
- Prompt 준수율 우수
- Hallucination 발생률이 가장 낮음

---

# 📄 License

MIT License
# YouTube LLM Prompt Engineering System

LLM을 활용한 유튜브 콘텐츠 제작 자동화 시스템입니다.

사용자가 영상 주제를 입력하면 AI가 콘텐츠 기획, 대본 작성, 제목 생성, 썸네일 문구 생성까지 수행하도록 Prompt Engineering 기반으로 설계하였습니다.

---

# Project Overview

## 목표

- LLM 기반 콘텐츠 제작 자동화
- Prompt 구조 설계
- Hallucination 방지
- 재사용 가능한 Prompt System 구축

---

# System Flow

