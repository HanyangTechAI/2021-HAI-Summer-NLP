# 2021 HAI Summer NLP
한양대학교 인공지능 동아리 HAI에서 2021년 여름에 진행된 NLP 기초 강의 자료입니다.
예제 자료와 과제는 [PyTorch](https://pytorch.org)를 사용합니다.


## Text Books
- 파이토치로 배우는 자연어 처리 (델립 라오, 브라이언 맥머핸 저/박해선 역, 2021)
- 한국어 임베딩 (이기창, 2019)


## Contents
- Week1 - Intro to NLP and PyTorch, Chapter 1 ~ 2 (7/27) [[YouTube](https://youtu.be/Bg3BEaZy_ys)] [[PDF](https://github.com/HanyangTechAI/2021-HAI-Summer-NLP/blob/master/Lectures/HAI_SUMMERNLP_01_Intro_to_NLP_and_PyTorch.pdf)] [[Practice](https://github.com/rickiepark/nlp-with-pytorch/tree/main/chapter_1)]
  - NLP에서의 머신러닝
  - 샘플과 타깃의 인코딩
  - 실습 : PyTorch 기초
  - NLP 기술 빠르게 훑어보기

- Week2 - Perceptron for Sentiment Classification, Chapter 3 (8/3) [[YouTube](https://youtu.be/3u2KGIkH-w4)] [[PDF](https://github.com/HanyangTechAI/2021-HAI-Summer-NLP/blob/master/Lectures/HAI_SUMMERNLP_02_Perceptron_for_Sentiment_Classification.pdf)] [[Practice](https://github.com/rickiepark/nlp-with-pytorch/tree/main/chapter_3)]
  - 퍼셉트론
  - 활성화 함수
  - 손실함수와 지도학습
  - 실습 : 레스토랑 리뷰 감성 분류하기

- Week3 - Feed Forward Neural Network for NLP, Chapter 4 (8/10) [[YouTube](https://youtu.be/yJzamd_2aYk)] [[PDF](https://github.com/HanyangTechAI/2021-HAI-Summer-NLP/blob/master/Lectures/HAI_SUMMERNLP_03_Feed_Forward_NN_for_NLP.pdf)] [[Practice](https://github.com/rickiepark/nlp-with-pytorch/tree/main/chapter_4)]
  - 다층 퍼셉트론 (MLP)
  - 실습 : NLP로 성씨 분류하기
  - 합성곱 신경망 (CNN)
  - 실습 : CNN으로 성씨 분류하기

- Week4 - Word Embedding, Chapter 5 (8/17) [[YouTube](https://youtu.be/IeUqmXhs9qU)] [[PDF](https://github.com/HanyangTechAI/2021-HAI-Summer-NLP/blob/master/Lectures/HAI_SUMMERNLP_04_Word_Embedding.pdf)] [[Practice](https://github.com/rickiepark/nlp-with-pytorch/tree/main/chapter_5)]
  - 임베딩의 역할
  - 임베딩의 원리
  - 실습 : CBOW 학습하기
  - 실습 : CBOW 사용하기

- Week5 - Sequence Modeling for NLP Part 1, Chapter 6 ~ 7 (8/24) [[YouTube](https://youtu.be/6iX9Id9oTw8)] [[PDF](https://github.com/HanyangTechAI/2021-HAI-Summer-NLP/blob/master/Lectures/HAI_SUMMERNLP_05_Sequence_Modeling_for_NLP_1.pdf)] [[Practice 1](https://github.com/rickiepark/nlp-with-pytorch/tree/main/chapter_6)] [[Practice 2](https://github.com/rickiepark/nlp-with-pytorch/tree/main/chapter_7)]
  - Elman RNN
  - 실습 : Surname Classification
  - Gating : LSTM and GRU
  - 실습 : Surname Generation

- Week6 - Sequence Modeling for NLP Part 2, Chapter 8 ~ 9 (8/31) [[YouTube](https://youtu.be/ANZSfHXVir4)] [[PDF](https://github.com/HanyangTechAI/2021-HAI-Summer-NLP/blob/master/Lectures/HAI_SUMMERNLP_06_Sequence_Modeling_for_NLP_2.pdf)] [[Practice](https://github.com/rickiepark/nlp-with-pytorch/tree/main/chapter_8)]
  - Sequence to Sequence
  - Bi-directional RNNs
  - Attention Mechanism
  - 실습 : Machine Translation
  - 고전모델, 최신모델, 더 배울 것들
