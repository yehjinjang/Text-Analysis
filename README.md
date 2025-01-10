# 📝 Text Analysis Projects

## 1. 영화 "Parasite(기생충)" 국내외 반응 분석 

### 📖 Overview
이 프로젝트는 텍스트 데이터 분석 수업의 일환으로, 영화 ‘기생충’의 황금종려상 수상 이후, YouTube 댓글을 분석하여 국내외 대중의 반응과 감정을 비교하였습니다.

---

### 🗓️ Period
- 2023년 7월 ~ 2023년 8월 (1개월)

---

### 👥 Team
- 개인 프로젝트 
---

### 🛠️ Tech Stack
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![VADER](https://img.shields.io/badge/VADER-NLP-green?style=for-the-badge) ![Logistic Regression](https://img.shields.io/badge/Logistic%20Regression-FF6F00?style=for-the-badge) ![Naive Bayes](https://img.shields.io/badge/Naive%20Bayes-blue?style=for-the-badge) ![SVM](https://img.shields.io/badge/SVM-purple?style=for-the-badge) ![LDA](https://img.shields.io/badge/LDA-orange?style=for-the-badge) 

---

### 🧑‍💻 Key Task
1. **데이터 수집**
   - YouTube Data API를 활용하여 'parasite' 키워드로 약 15,000개의 영화 리뷰 댓글 수집

2. **전처리**
   - Python 내장 함수와 treebank tokenizer를 이용해 데이터 클리닝 및 토큰화 수행
   - Stopword 제거 및 단어 길이에 따른 필터링 진행

3. **감성 분석**
   - VADER를 이용해 댓글의 긍정, 부정, 중립 감성을 레이블링

4. **모델링**
   - Tf-idf를 활용하여 벡터화 진행.
   - SVM, Logistic Regression, Naïve Bayes, MLP 모델을 활용해 감성 예측 정확도 비교

5. **토픽 모델링**
   - LSA, LDA를 통해 주요 토픽 도출 및 시각화

---

### 🌟 Retrospective
이번 프로젝트를 통해 데이터를 라벨링하는 작업의 중요성을 알게 되었으며, 감성 분석과 토픽 모델링의 효용성을 확인하였습니다. YouTube 데이터를 활용해 대중의 감정을 파악하며 텍스트 데이터 분석의 가능성을 체감할 수 있었습니다.

---

## 2. 내 호텔을 찾아라 (Text Mining)

### 📖 Overview
이 프로젝트는 개인 사이드 프로젝트의 일환으로, 국내 여행 계획 시 호텔 선택을 돕기 위해 호텔 리뷰 데이터를 텍스트 마이닝 기법으로 분석하였습니다.

---

### 🗓️ Period
2022년 8월 ~ 2022년 9월 (1개월)

---

### 👥 Team
개인 프로젝트 

---

### 🛠️ Tech Stack
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white) 
![Konlpy](https://img.shields.io/badge/Konlpy-00BFFF?style=for-the-badge) ![NLP](https://img.shields.io/badge/NLP-blue?style=for-the-badge) ![TF-IDF](https://img.shields.io/badge/TF-IDF-yellowgreen?style=for-the-badge)

---

### 🧑‍💻 Key Task
1. **데이터 수집**
   - Selenium을 이용해 야놀자 플랫폼에서 1,465개의 호텔 리뷰 데이터를 크롤링

2. **데이터 전처리**
   - Konlpy로 형태소 분석 및 명사 추출
   - 불용어 제거 및 데이터 클리닝을 통해 주요 키워드만 추출

3. **분석 및 시각화**
   - 단어 빈도수를 기반으로 워드 클라우드 및 시각화 진행
   - TF-IDF를 활용하여 각 호텔 리뷰에서 중요한 키워드 도출

4. **결과 해석**
   - 고객 리뷰에서 “청결함”과 “직원 서비스”와 같은 키워드의 중요성을 확인

---

### 🌟 Retrospective
데이터가 실제 비즈니스에 미치는 영향을 체감할 수 있었던 프로젝트였습니다. 특히, 고객 리뷰를 통해 얻을 수 있는 인사이트의 실무적 활용 가능성을 확인하였으며, 자연어 처리 기술의 강점을 이해하는 데 많은 도움이 되었습니다.
