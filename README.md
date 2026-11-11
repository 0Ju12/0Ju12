## 안녕하세요, 이영주입니다 👋

**데이터·AI 엔지니어** · 복잡한 지구과학 데이터를 딥러닝과 분석으로 풀어냅니다.

- 🌍 중력·자력 데이터 **파수 상관 분석**으로 지하 구조 규명 — SCIE *SPE Journal* 제1저자 · 분석 코드 [gravmag-wcf](https://github.com/0Ju12/gravmag-wcf) · 브라우저에서 해 보기 [WCF 실험실](https://0ju12.github.io/data-projects/wcf/)
- 🔬 학부연구생 제1저자 논문 — 판구조 형성사를 고려한 해외 대규모 CO2 저장소 탄성파 해석 · IAB 융합전공 시공간 딥러닝(U-LSTM) **산불 확산 예측**
- 💻 삼성 청년 SW·AI 아카데미(SSAFY) 16기 — LLM 데이터 파이프라인 [ThRead](https://github.com/0Ju12/ssafy-thread) · 근거 인용 RAG [국보 입문 가이드](https://github.com/0Ju12/heritage-rag-guide) · AI 챌린지 VQA 앙상블 Public 0.96961
- 🗣️ 포스코 청년 AI·BigData 아카데미 30기 — 콩글리시 교정 FLAN-T5 + RAG (POSPEAK/KILL KONG) · 장려상
- 🎓 전북대학교 환경에너지융합학과 석사 (2026) · 자원에너지공학과 학사 · ADsP

📄 **포트폴리오 & 이력서 → [0ju12.github.io](https://0ju12.github.io)**  ·  ✉️ iyju990312@naver.com  ·  💼 [LinkedIn](https://www.linkedin.com/in/%EC%98%81%EC%A3%BC-%EC%9D%B4-a335ab251/)

---

### 📌 대표 프로젝트

| 프로젝트 | 내용 | 기술 |
|---|---|---|
| [**🌍 gravmag-wcf — 중력·자력 파수 상관 필터링**](https://github.com/0Ju12/gravmag-wcf) | 석사 연구 코드. 겹친 중력·자력 신호를 파수별 위상 상관 CC(k)로 나눠 기반암(SLFI)·암염(DLFI) 지표를 만들고, 임계값을 에너지-상관 곡선으로 근거화. 합성 데이터 예제·테스트·CI 포함 | NumPy FFT · SciPy · pytest |
| [**🔥 산불 확산 경로 예측**](https://github.com/0Ju12/wildfire-spread-prediction) | IAB 융합전공 캡스톤. 화선·기상·지형 래스터로 다음 시점의 산불 확산을 예측하는 U-LSTM. 모델 설계·학습 담당 · 미학습 산불 테스트 Accuracy 0.90 · F1 0.85 | TensorFlow · rasterio · ArcGIS |
| [**💻 ThRead — LLM 댓글 분석 파이프라인**](https://github.com/0Ju12/ssafy-thread) | SSAFY 관통 프로젝트. Selenium 수집 → LLM 판단을 코드로 검증 → pandas 정제·증강·요약, Django 서비스. 자동 테스트 142개 | Django · Selenium · LLM API |
| [**🏛️ 국보 입문 가이드 — 근거 인용 RAG**](https://github.com/0Ju12/heritage-rag-guide) | 국가유산청 오픈API·위키백과 수집 → ChromaDB → LangGraph RAG. 답변의 근거 번호를 코드로 검증해 실제 인용한 근거만 표시. 오프라인 테스트 55개 · 답변 품질 평가 도구 | LangGraph · ChromaDB · Streamlit · FastAPI |
| [**📊 data-projects — 공개 데이터 프로젝트 4종**](https://github.com/0Ju12/data-projects) | USGS 지진 증분 수집·대시보드(매일 자동 갱신) · 설비 센서 이상 탐지(무작위 0.99 → 시간 분할 0.46으로 부풀려진 성능 확인) · 전력거래소 수요 하루 전 예측(MAPE 3.23%, [예측 탐색기](https://0ju12.github.io/data-projects/power/)) · DART SQL 데이터 마트 | Python · SQL · scikit-learn · GitHub Actions |
| [**🔥 산불 위험 지도 · 🤖 데이터 에이전트**](https://github.com/0Ju12/data-projects) | [산불 위험 지도](https://0ju12.github.io/data-projects/fire/): 화재기상지수와 NASA 위성 탐지를 매일 비교(탐지의 90%는 제철소 등 상시 열원 → 가려내는 규칙). data-agent: 위 데이터를 LLM 이 조회하는 MCP 서버, SQL 안전장치와 답 속 숫자 검증 | Python · SQLite · MCP · GitHub Actions |
| [**🧩 swea-solutions — SWEA 풀이 모음**](https://github.com/0Ju12/swea-solutions) | SSAFY에서 푼 SWEA 36문제를 주제별(구현·그래프·백트래킹/DP·문자열)로 정리. 직접 만든 입력 테스트 37개, 테스트로 찾은 오류 6개는 고친 내용을 README에 기록 | Python · pytest · GitHub Actions |
| [**🗣️ 콩글리시 → 원어민 표현 교정**](https://github.com/POSCO-AI-BigData-30th/ai-pospeak/tree/db2-t5) | FLAN-T5 LoRA 파인튜닝 + FAISS 기반 RAG. 데이터 구축·학습 전략 비교 실험 담당 (BERTScore F1 0.74) | Hugging Face · PEFT · FAISS |

### 📝 논문
- **Lee, Y.-J.** et al. (2026). *Wavenumber Correlation of Gravity and Magnetic Anomalies for Constraining Salt/Basement Structure in Offshore Abu Dhabi.* **SPE Journal** (SCIE). [DOI](https://doi.org/10.2118/236968-PA)
- **이영주** 외 (2024). 판구조론적 역사를 고려한 해외 대규모 이산화탄소 지중저장소 탄성파 해석 결과 분석. *지구물리와 물리탐사*, 27(1). [링크](https://koreascience.or.kr/article/JAKO202410348585789.page)
- **이영주** (제2저자) 외 (2023). 호주 깁스랜드 분지 CarbonNet CCS 프로젝트의 지질학적 분석. *지구물리와 물리탐사*. [링크](https://koreascience.or.kr/article/JAKO202335272000266.page)

### 🛠 기술
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![ArcGIS](https://img.shields.io/badge/ArcGIS-2C7AC3?style=flat-square&logo=arcgis&logoColor=white)

`딥러닝(CNN·LSTM)` `LLM 파인튜닝(LoRA·QLoRA)` `멀티모델 앙상블` `RAG` `공간·래스터 데이터` `신호처리` `중력·자력·탄성파 자료 해석`

### 🌏 경험
- 🇨🇦 University of Calgary 파견연구 2회 (2023–2024) — 중력·자력 데이터 복합 해석
- 🏆 KSEG 봄 학술대회 학생 우수논문 발표상 (2024) · 포스코 AI·Big Data 아카데미 장려상 (2025)
