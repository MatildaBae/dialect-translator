# **💬 Gyeong Sang do-Seoul Dialect Translator** 🌐
*Transform your sentences from Standard Korean to 경상도 Dialect effortlessly!*

## 🚀 **Project Overview**
Welcome to our 경상도-표준어 Dialect Translator project! This repository is the culmination of our journey to bridge the linguistic gap between Standard Korean and the rich 경상도 dialect, using cutting-edge Transformer models. 

### **Why This Project?**
Dialect translation is an under-explored area in Natural Language Processing (NLP). While much focus is given to translating between different languages, regional dialects pose unique challenges and opportunities. Inspired by the scarcity of such tools, especially for Korean dialects, we embarked on this project to provide a seamless translation experience.

## 🧠 **How It Works**
This translator leverages the **Transformer architecture**—the same technology that powers many state-of-the-art NLP models. By training on a curated dataset of 경상도 dialect and standard Korean sentences, our model learns the nuanced linguistic patterns and delivers accurate translations.

### **Tokenizer & Preprocessing**
To prepare our dataset for the Transformer model, we implemented several key preprocessing steps:

- **Data Cleaning**: Removed special characters and non-Korean text using regular expressions to maintain data consistency.
- **Tokenization**: Used a morpheme-based tokenization approach for Standard Korean input and word-level tokenization for 경상도 dialect output. This allowed for better handling of the linguistic variations between the two forms.
- **Handling Irregularities**: Managed outliers and irregular data patterns, such as colloquialisms and speech disfluencies, which are common in dialect data.

These preprocessing steps ensured that the data fed into the model was of high quality, leading to more accurate translations.

### **Key Features**
- **Dialect Awareness**: Translates Standard Korean sentences into authentic 경상도 dialect.
- **Transformer Model**: Based on the "Attention is All You Need" architecture.
- **Performance Optimized**: Fine-tuned with BLEU score evaluation to ensure high-quality output.


## 📈 **Results**
Our model has been tested rigorously, achieving impressive BLEU scores that reflect its translation accuracy:

- **Model Version 1**: BLEU Score - *0.7643*
- **Model Version 2**: BLEU Score - *0.6826*

## 📄 **License**
This project is licensed under the MIT License—see the LICENSE file for details.

# **경상도-표준어 방언 번역기** 🌐

경상도-표준어 방언 번역기 리포지토리에 오신 것을 환영합니다. 이 프로젝트는 고려대학교 데이터 사이언스 & 인공지능 학회 KUBIG 팀에 의해 개발되었으며, 팀원은 박제재, 박세훈, 심승현, 배지원, 정하연입니다. 이 번역기는 표준어 문장을 경상도 방언으로 변환하는 기능을 제공합니다.

## 📄 **프로젝트 개요**
본 프로젝트는 표준어와 경상도 방언 간의 언어적 차이를 보다 쉽게 극복할 수 있도록 돕기 위해 기획되었습니다. 최근 NLP(자연어 처리) 기술의 발전을 바탕으로, Transformer 모델을 사용하여 한국어 방언 번역이라는 도전적인 과제를 해결하고자 하였습니다.

## 💡 **주요 기능**

- **방언 번역**  
  - **대상 사용자**: 경상도 방언을 이해하고 사용하는 데 어려움을 겪는 사용자
  - **구성 요소**: 표준어 입력 문장을 실시간으로 경상도 방언으로 변환
  - **커스터마이징**: 사용자의 입력 문장에 따라 최적의 번역 결과 제공

## 📊 **데이터 및 모델**

- **모델**: 본 프로젝트에서는 "Attention is All You Need" 논문을 기반으로 한 Transformer 모델을 사용하여 표준어와 경상도 방언 간의 번역을 수행합니다.
- **데이터셋**: 모델 학습을 위해 경상도 방언 발화 데이터와 표준어 데이터를 사용하였습니다. 이 데이터는 AI 허브에서 제공된 자료를 기반으로 하여, 방언의 다양한 표현을 포괄하도록 구축되었습니다.

## 📂 **프로젝트 구조**

1. **데이터 수집 및 전처리**
   - **데이터 정제**: 원본 데이터셋에서 불필요한 문자를 제거하고, 구어체의 특성을 반영하여 정리하였습니다.
   - **토크나이징**: 형태소 분석 및 어절 단위 토크나이징을 통해 모델 학습에 적합한 형식으로 데이터를 변환하였습니다.

2. **모델 학습 및 평가**
   - **모델 구조**: 인코더-디코더 구조를 갖춘 Transformer 모델을 사용하여, 표준어와 방언 간의 번역 작업을 수행합니다.
   - **성능 평가**: BLEU 점수를 사용하여 번역 성능을 평가하고, 모델의 품질을 측정하였습니다.

3. **번역 예시 및 결과**
   - 학습된 모델을 바탕으로 새로운 문장을 입력하여 번역 결과를 도출하고, 다양한 예시를 통해 번역의 정확성을 검증하였습니다.

## 📈 **결과**
모델은 다양한 실험을 통해 평가되었으며, BLEU 점수 기준으로 우수한 번역 성능을 보였습니다:

- **모델 버전 1**: BLEU 점수 - *0.7643*
- **모델 버전 2**: BLEU 점수 - *0.6826*

## 📄 **라이선스**
이 프로젝트는 MIT 라이선스 하에 배포됩니다. 자세한 내용은 LICENSE 파일을 참조하시기 바랍니다.

## 🙏 **감사 인사**
고려대학교 데이터 사이언스 & 인공지능 학회 KUBIG 팀원들께 깊은 감사를 드립니다.

