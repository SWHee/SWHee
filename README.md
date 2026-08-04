<div align="center">

# Geonhee Jo

**Python Backend · LLM/RAG · Evaluation**

모델 호출에서 멈추지 않고, 검색 근거와 평가까지 이어지는 AI 서비스를 만들고 있습니다.

<br>

**카카오테크 부트캠프 4기 · AI 실무 개발 과정**  
<sub>2026.05 – 2026.11</sub>

</div>


<br/>

<div align="center">

<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="https://github-stats-extended.vercel.app/api?username=SWHee&show_icons=true&custom_title=Geonhee%27s%20GitHub%20Stats&title_color=C41E3A&text_color=c9d1d9&icon_color=C41E3A&bg_color=00000000&hide_border=true&include_all_commits=true&rank_icon=github"
  />
  <source
    media="(prefers-color-scheme: light)"
    srcset="https://github-stats-extended.vercel.app/api?username=SWHee&show_icons=true&custom_title=Geonhee%27s%20GitHub%20Stats&title_color=C41E3A&text_color=24292f&icon_color=C41E3A&bg_color=00000000&hide_border=true&include_all_commits=true&rank_icon=github"
  />
  <img
    src="https://github-stats-extended.vercel.app/api?username=SWHee&show_icons=true&custom_title=Geonhee%27s%20GitHub%20Stats&title_color=C41E3A&text_color=c9d1d9&icon_color=C41E3A&bg_color=00000000&hide_border=true&include_all_commits=true&rank_icon=github"
    height="180"
    alt="Geonhee's GitHub Stats"
  />
</picture>
&nbsp;&nbsp;
<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="https://github-stats-extended.vercel.app/api/top-langs/?username=SWHee&title_color=C41E3A&text_color=c9d1d9&bg_color=00000000&hide_border=true&layout=compact&langs_count=8"
  />
  <source
    media="(prefers-color-scheme: light)"
    srcset="https://github-stats-extended.vercel.app/api/top-langs/?username=SWHee&title_color=C41E3A&text_color=24292f&bg_color=00000000&hide_border=true&layout=compact&langs_count=8"
  />
  <img
    src="https://github-stats-extended.vercel.app/api/top-langs/?username=SWHee&title_color=C41E3A&text_color=c9d1d9&bg_color=00000000&hide_border=true&layout=compact&langs_count=8"
    height="180"
    alt="Most Used Languages"
  />
</picture>

<br/><br/>

<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="https://streak-stats.demolab.com?user=SWHee&hide_border=true&background=0d1117&ring=C41E3A&fire=C41E3A&currStreakLabel=C41E3A&sideLabels=c9d1d9&currStreakNum=c9d1d9&sideNums=c9d1d9&dates=6e7681"
  />
  <source
    media="(prefers-color-scheme: light)"
    srcset="https://streak-stats.demolab.com?user=SWHee&hide_border=true&background=ffffff&ring=C41E3A&fire=C41E3A&currStreakLabel=C41E3A&sideLabels=24292f&currStreakNum=24292f&sideNums=24292f&dates=57606a"
  />
  <img
    src="https://streak-stats.demolab.com?user=SWHee&hide_border=true&background=0d1117&ring=C41E3A&fire=C41E3A&currStreakLabel=C41E3A&sideLabels=c9d1d9&currStreakNum=c9d1d9&sideNums=c9d1d9&dates=6e7681"
    alt="GitHub Streak"
  />
</picture>

</div>

<br/>


## Tech Stack

**Backend**

![Python](https://img.shields.io/badge/Python-111827?style=flat&logo=python&logoColor=FFD43B)
![FastAPI](https://img.shields.io/badge/FastAPI-111827?style=flat&logo=fastapi&logoColor=00C7B7)
![Django](https://img.shields.io/badge/Django-111827?style=flat&logo=django&logoColor=44B78B)
![Redis](https://img.shields.io/badge/Redis-111827?style=flat&logo=redis&logoColor=FF4438)

**LLM & RAG**

![PyTorch](https://img.shields.io/badge/PyTorch-111827?style=flat&logo=pytorch&logoColor=EE4C2C)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-111827?style=flat&logo=huggingface&logoColor=FFD21E)
![LangChain](https://img.shields.io/badge/LangChain-111827?style=flat&logo=langchain&logoColor=FFFFFF)
![LangGraph](https://img.shields.io/badge/LangGraph-111827?style=flat&logo=langchain&logoColor=FFFFFF)
![LangSmith](https://img.shields.io/badge/LangSmith-111827?style=flat)
![Chroma](https://img.shields.io/badge/Chroma-111827?style=flat)

**Computer Vision**

![OpenCV](https://img.shields.io/badge/OpenCV-111827?style=flat&logo=opencv&logoColor=5C3EE8)


## Projects

### [Korean Chatbot Lab](https://github.com/SWHee/korean-chatbot-lab)

`Current Project`

금융소비자보호법과 예금자보호법을 근거로 답변하는 한국어 RAG 챗봇입니다.

- Qwen3를 Ollama와 Hugging Face 기반의 교체 가능한 생성기로 구성
- 법령 조문 청킹, KURE-v1 임베딩, Chroma 검색을 연결한 RAG 파이프라인 구현
- FastAPI 일반·스트리밍 API와 Streamlit 채팅 화면 개발
- LangSmith Dataset과 평가 흐름을 이용한 검색 및 답변 품질 검증

### [ALF Knowledge Quality Gate](https://github.com/SWHee/channeltalk-codex-plugin)

`AX 인재전쟁 해커톤 본선 진출`

채널톡 AI 에이전트 ALF에 등록할 지식 문서를 배포 전에 감사하는 Codex 플러그인입니다.

- 문서 간 충돌, 조건 누락, 모호한 표현, 만료 가능성, 민감정보를 심각도별로 분류
- 모든 지적 사항을 원문 인용과 연결하고 감사 리포트, 최소 수정안, ALF 회귀 테스트를 생성
- 결정적 Python 스크립트로 결과 스키마와 인용 근거를 검증하고, 중대한 문제가 남으면 배포 단계 차단

### [AIdeaChat](https://github.com/SWHee/AIdeaChat)

`2024 Capstone Design · Archive`

실시간 채팅과 일정 관리에 문서 요약, OCR, STT 기능을 결합한 협업 플랫폼입니다.

- Django Channels와 Redis를 이용한 그룹·1:1 WebSocket 채팅 구현
- 이미지와 PDF를 지원하는 OCR 전처리 및 파일 처리 기능 구현
- SpeechRecognition의 Google Web Speech API 연동을 이용한 한국어 STT 기능 구현
- Django 웹 화면과 React Native 프로토타입의 UI 디자인 및 세부 요소 개선
- Django 웹 애플리케이션과 React Native 모바일 프로토타입 구성


## Credentials

- **정보처리기사** — 2024.09
- **SQLD** — 2026.03
- **ADsP** — 2026.03
- **OPIc IM3** — 2025.01
