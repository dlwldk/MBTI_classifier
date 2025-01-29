# MBTI_classifier
KoBERT 모델을 사용하여 MBTI(성격 유형 지표)를 분류

## 데이터: Hugging Face의 mbti_dataset.csv
- text: 해당 성격 유형의 개인이 작성한 텍스트 데이터
- label: MBTI 성격 유형을 나타내는 문자열 (예: 'intj', 'enfp')
- text의 띄어쓰기는 [SEP]으로 구분 - [SEP] 토큰은 BERT와 같은 Transformer 모델에서 문장 또는 개념을 분리하는 역할
