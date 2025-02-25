# 자연어처리(NLP)와 머신러닝을 이용한 리뷰 데이터 분석 및 사용자 경험 분석

-------

### 프로젝트 진행 : 21/04/05 ~ 21/11/30 

### 팀원 소개
- 박정빈 (세종대학교 지능기전공학부 스마트기기공학전공) 
- 박승일 (세종대학교 지능기전공학부 스마트기기공학전공) 
- 이재훈 (세종대학교 지능기전공학부 스마트기기공학전공)
- 멘토: 박재범 (LG CNS)
### 프로젝트 소개 

온라인 쇼핑몰에서 소비자가 많은 고민과 시간 투자 없이 상품을 선택, 평가할 수 있도록 지원하고 소비자 특징에 맞춰 도움이 될 만한 상품을 적절하게 추천하는 서비스



### 주요기능

| 기능             | 설명                                                         |
| ---------------- | ------------------------------------------------------------ |
| 감성분석 ( XAI ) | 상품 리뷰 데이터를 분석하여, 해당 상품이 긍정 리뷰인지, 부정 리뷰인지 예측합니다. 이 과정에 XAI를 도입하여, 어떠한 단어의 영향으로 긍정 혹은 부정으로 구분하였는지 노출합니다. |
| 키워드 추출      | 상품 리뷰 데이터를 분석하여, 해당 리뷰에 핵심 키워드들을 추출합니다. |
| 리뷰 요약        | 키워드 추출을 통해 추출된 키워드에 대한 전체적인 평가를 가장 잘 반영하는 문장으로 요약합니다. |
| 절대평점         | 상품 구매자가 직접 상품에 대한 평점을 부여하는 방식이 아닌, 리뷰 데이터 분석을 통해 상품에 절대적인 평점을 부여합니다. |
| 트렌드분석       | 트렌드 분석을 통해, 해당 카테고리의 정보를 시각화합니다.     |
| 상품추천         | 추출된 키워드에서 고려하고 싶은 키워드 선택 시 해당 키워드 바탕으로 상품을 추천합니다. |



### 작품 개발 환경

| 구분           | 상세내용                                  |
| -------------- | ----------------------------------------- |
| OS             | Windows 10                                |
| 개발환경       | Google Colab, Pycharm, Visual studio Code |
| Cloud Compute  | AWS EC2                                   |
| Web server     | Django                                    |
| Database       | SQLite                                    |
| Front-end      | HTML / CSS                                |
| 개발언어       | Python / JavaScript                       |
| Word Embedding | Word2Vec                                  |
| Tokenizer      | Konlpy Mecab                              |
| 형상관리       | Git                                       |
| 소통           | Slack / Kakao Talk                        |

### 시연 영상
https://www.youtube.com/watch?v=BmTeiVTbjN4

### 작품 사진

<img src="/readme_image/main.PNG">
<img src="/readme_image/리뷰요약.PNG">
<img src="/readme_image/xai_goodimg.png">
<img src="/readme_image/상품추천.PNG">
<img src="/readme_image/상세리뷰.PNG">
