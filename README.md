## 송수빈 · suvinn

부스트캠프 AI Tech에서 NLP 모델을, SSAFY에서 AI 서비스 백엔드를 만들었습니다.  
어느 쪽이든 데이터부터 들여다보는 편이라 증강·정제·분류처럼 데이터를 다루는 일을 가장 많이 맡았습니다.

[![Email](https://img.shields.io/badge/ssongsuvin@naver.com-0F766E?style=flat-square&logo=naver&logoColor=white)](mailto:ssongsuvin@naver.com)
[![Velog](https://img.shields.io/badge/velog-@suvinn-20C997?style=flat-square&logo=velog&logoColor=white)](https://velog.io/@suvinn/posts)

<br>

### 걸어온 길

- **2026.07 – 2026.08** · 하나은행 AI/ICT 체험형 인턴 우수 수료자 선정
- **2026.01 – 2026.06** · 삼성 청년 SW·AI 아카데미 15기 (1학기 이수)
- **2025.07 – 2025.08** · SK AI Dream Camp 중급 우수 학습자 선정
- **2024.08 – 2025.02** · 네이버 부스트캠프 AI Tech 7기 NLP 트랙

<br>

### 프로젝트

#### AI 서비스

| 레포 | 무엇을 만들었나 | 내가 맡은 일 |
|---|---|---|
| [**ai-math-coach**](https://github.com/suvinn/ai-math-coach)<br><sub>WIDN Math · SSAFY · 2026.05–06</sub> | 중2 수학 유형별 약점 분석, 보완 문제 추천, 풀이 챗봇 | 백엔드·데이터 전담 — 1,770문항 정제와 유형 분류, REST API, LangGraph 코칭·가드레일 챗봇, ChromaDB 유사 문제 추천 |
| [**make-your-sports**](https://github.com/suvinn/make-your-sports)<br><sub>공공데이터 경진대회 출품 · 2026.09</sub> | 사주 오행과 자연어 조건으로 동네 공공체육 강좌 추천 | 서비스 구현 — 공공데이터 전처리, Claude API 조건 파싱(실패 시 규칙 기반으로 대체), Streamlit 화면 |
| [**clovista**](https://github.com/suvinn/clovista)<br><sub>부스트캠프 × 네이버 클라우드 해커톤 · 2025.01–02</sub> | HyperCLOVA X 기반 인플루언서 지원 서비스 | 댓글 반응·논란 가능성 분석 모델 실험, 과거 논란 사례 유형화와 사례 제시 백엔드 |

#### NLP 모델링 · 부스트캠프 AI Tech

| 레포 | 무엇을 만들었나 | 내가 맡은 일 |
|---|---|---|
| [**boostcamp-ksat-solver**](https://github.com/suvinn/boostcamp-ksat-solver)<br><sub>2024.11</sub> | LLM 파인튜닝으로 한국어 수능 문제 풀기 | EDA, 외부 데이터 증강(KBS 한국어능력시험 · SAT history · KorQuAD), 사전학습 실험 |
| [**boostcamp-datacentric**](https://github.com/suvinn/boostcamp-datacentric)<br><sub>2024.11</sub> | 모델은 그대로 두고 데이터만 고쳐 뉴스 헤드라인 주제 분류 성능 높이기 | LangChain + Gemma2 헤드라인 증강, Not Noisy 데이터 증강, Cleanlab 재라벨링 (부족한 라벨을 Gemma2 생성 데이터로 보충한 조합이 최고 성능) |
| [**boostcamp-odqa**](https://github.com/suvinn/boostcamp-odqa)<br><sub>2024.10</sub> | 위키 문서 검색과 답 추출로 만든 오픈도메인 QA | Extraction Reader 학습, WandB Sweep 튜닝, 앙상블과 모델 간 상관관계 분석 |
| [**boostcamp-sts**](https://github.com/suvinn/boostcamp-sts)<br><sub>2024.09</sub> | 두 문장의 의미 유사도(0–5) 예측 | 데이터 증강 — 다운샘플링, 문장 순서 교체, BERT 마스킹 삽입, 맞춤법 교정 (마스킹 삽입으로 Pearson 0.9232 → 0.9300) |

<br>

### 기술

| 분야 | 기술 | 써본 곳 |
|---|---|---|
| 백엔드 | Python · Django REST Framework · FastAPI · Streamlit · SQLite | ai-math-coach · clovista · make-your-sports |
| LLM 서비스 | LangGraph · ChromaDB(RAG) · OpenAI API · Claude API · HyperCLOVA X | ai-math-coach · make-your-sports · clovista |
| NLP 모델링 | PyTorch · Hugging Face Transformers · WandB · LangChain · Cleanlab | boostcamp-sts · boostcamp-odqa · boostcamp-datacentric · boostcamp-ksat-solver |
| 협업 | Git · GitHub PR 리뷰 · Notion · Slack | morgorithm · 부스트캠프 팀 프로젝트 |

<br>

### 스터디

- [**morgorithm**](https://github.com/suvinn/morgorithm) · SSAFY 서울 2반 알고리즘 스터디 (2026.03) — 매일 한 문제, 전원 승인 PR 코드 리뷰
