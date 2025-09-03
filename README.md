# obsidian-notes
# Data Science Self-Study Log

이 리포지토리는 Kaggle 대회와 Python 학습을 진행하면서,  
학습 과정과 문제 해결 기록을 남기기 위해 만들었습니다.  
단순히 결과물이 아닌 **과정(Process)** 을 보여주는 것을 목표로 합니다.

---

## 📆 Timeline

### 2025-08-29
- Obsidian Vault 생성 및 GitHub Repo 연동 시작
- Python 실습 문제 풀이 (원 넓이 계산, 문자열 전처리, 결측 평균 처리)

### 2025-08-30
- GitHub 첫 Repo 생성 (`kaggle-house-prices`)
- `01_eda_initial.ipynb` 작성 시작 (train.csv 불러오기 & head 확인)
- README.md 작성 및 업로드

### 2025-08-31
- Obsidian Git 플러그인 설치 및 Vault 자동 백업 설정
- .gitignore, .gitattributes 설정 → 불필요 파일 제외
- Templater 플러그인으로 Daily / Kaggle / Python 학습 템플릿 작성
- Daily Note에 학습 계획/체크리스트 기록 시작
### 2026-09-03
- 데이터셋: Titanic (train.csv, 891행 x 12열)
- 구조 확인: `train.info()` -> 주요 컬럼 타입 및 결측치 확인
- 기본 통계: `train.dexcribe()` -> Fare, Age 등 분포 확인
- 결측치 요약: `isnull().sum()` -> Age(177), Cabin(687), Embarked(2) 등 결측 다수
- 다음 단계: Age 분포 시각화, Sex.Pclass별 생존률 분석

---

## 🛠️ Tech Stack & Tools
- **Python** (Pandas, Numpy, Matplotlib)
- **Kaggle Notebooks** (EDA, 모델링)
- **GitHub** (코드 및 노트 버전관리)
- **Obsidian + Templater + Obsidian Git** (학습 기록 자동화)

---

## 🎯 Goal
- Kaggle 대회 참여 & 기록
- 데이터 전처리 → 모델링 → 결과 해석의 전 과정을 문서화
- GitHub에 코드 + Obsidian 노트 모두 기록하여,  
  **학습 성장 과정이 보이는 포트폴리오** 완성
