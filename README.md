# Seoul Rent Price Analysis

전월세 실거래 데이터를 전처리하고 EDA 및 회귀 모델링을 통해 임대료 예측 가능성을 분석한 프로젝트입니다.

## Overview

이 프로젝트는 서울 전월세 데이터를 기반으로 보증금, 월세, 면적, 자치구, 건축년도, 건물용도 등의 변수를 정리하고 임대료 예측 모델을 구성하는 것을 목표로 합니다.

## Project Structure

```text
rent-price-analysis/
├── README.md
├── .gitignore
├── .env.example
├── requirements.txt
├── data/
│   ├── raw/
│   │   └── README.md
│   └── processed/
│       └── README.md
├── notebooks/
│   └── README.md
├── reports/
│   └── README.md
├── src/
│   └── README.md
└── docs/
    └── project_summary.md
```

## Data

대용량 CSV 파일은 GitHub에 올리지 않습니다. 현재 확인된 로컬 데이터 파일은 다음과 같습니다.

```text
C:\Users\1604j\Downloads\seoul_final_processed_jeonse.csv
C:\Users\1604j\Downloads\seoul_final_processed_wolse.csv
```

두 파일 모두 GitHub 일반 파일 제한인 100MB를 초과하므로 `.gitignore`에서 제외합니다.

## Local Source Files

현재 로컬에서 확인된 분석 파일은 다음과 같습니다.

```text
C:\Users\1604j\Downloads\seoul_home.ipynb
C:\Users\1604j\Downloads\인개론부동산.ipynb
C:\Users\1604j\Downloads\인개론PJ_k_fold.ipynb
C:\Users\1604j\Downloads\data_process.ipynb
C:\Users\1604j\Downloads\서울_전월세_임대가격예측_비즈니스로직_보고서.docx
```

GitHub에는 우선 프로젝트 구조와 설명을 올리고, 노트북은 개인정보나 절대경로, 대용량 출력이 없는지 확인한 뒤 선별적으로 추가하는 것을 권장합니다.

## Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook
- Matplotlib / Seaborn

## Workflow

1. Raw data preparation
2. Data cleaning
3. Feature engineering
4. EDA
5. Regression modeling
6. Evaluation
7. Report summary

## GitHub Upload Policy

Included:

- README and documentation
- Project folder structure
- Requirements file
- Environment variable template

Excluded:

- `.env`
- Raw and processed CSV data
- Model artifacts
- Cache files
- Notebook checkpoints
- Local-only files

## Next Steps

- [ ] Clean notebooks and remove local absolute paths
- [ ] Add representative plots to `reports/figures/`
- [ ] Add model evaluation table
- [ ] Write detailed troubleshooting section
- [ ] Create GitHub repository
