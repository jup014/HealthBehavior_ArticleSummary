# Naldi(2019)
# 논문
- A review of sentiment computation methods with R packages
- [Arxiv 링크](https://arxiv.org/abs/1901.08319), https://arxiv.org/abs/1901.08319

# 저자
* **Dpt. of Civil Engineering and Computer Science, University of Rome Tor Vergata** - Maurizio Naldi

---

# 초록
- 감정분석(sentiment analysis)를 수행하는 데 도움이 되는 4가지 R 모듈을 분석함
- 4가지 모두 직접 만든 사전을 사용할 수 있었음
- 1개 (SentimentR)만 부정어의 존재를 제대로 반영했음


# 주요내용
## 도입
1. 감성 분석은 현재 사용 가능한 비정형 데이터의 크기 때문에 연구 및 응용 분야가 증가하고 있음 [5, 6].
2. 텍스트 마이닝, 특히 감정 분석에 사용되는 주요 알고리즘을 설명하는 많은 교과서가 출판되었음 [15, 3, 5].
3. 감정 분석을 위해 주로 자주 사용되는 언어는 Python과 R 인 것으로 보임 [13, 14]. 
4. R 내에서 감정 분석을 위한 패키지가 여럿 있음
5. 코딩 양을 줄여주지만, 폭과 정확성이 다르기 때문에 가장 적합한 패키지를 선택하는 문제가 존재

## 패키지들
1. 감정을 분석하는 기능을 포함한 패키지들을 대상으로 함.
2. 감정 분석은 여러 수준이 있음
    - 문장단위
    - 문장세트
    - 문장세트의 세트

이 백서에서 검토중인 패키지는 다음과 같습니다.
• syuzhet;
• Rsentiment;
• SentimentR;
• SentimentAnalysis.

3. 이들 모두 유사한 기능을 제공함. 감정분석 결과를 수치로 제공함.
4. 비교분석 결과, SentimentR이 다소 느리긴 해도 유일하게 부정어 인식을 하기 때문에, 나머지에 비해서 우월함

---

## Citation
- Mohammad, S., & Turney, P. (2018). Emotions Evoked by Common Words and Phrases: Using Mechanical Turk to Create an Emotion Lexicon, Proceedings of the {NAACL}-HLT 2010 Workshop on Computational Approaches to Analysis and Generation of Emotion in Text. Proceedings of the NAACL HLT 2010 Workshop on Computational Approaches to Analysis and Generation of Emotion in Text, 14(June), 26–34. http://www.wjh.harvard.edu/