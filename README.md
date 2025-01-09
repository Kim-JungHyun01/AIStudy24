# AIStudy24
Python 머신러닝, 딥러닝 학습용 2024

## 참고자료
- [Matplotlib Tutorial - 파이썬으로 데이터 시각화하기](https://wikidocs.net/book/5011#google_vignette)
  
## 정리
[k-최근접 알고리즘 정리](https://github.com/Kim-JungHyun01/AIStudy24/blob/master/%EC%A0%95%EB%A6%AC/k_%EC%B5%9C%EA%B7%BC%EC%A0%91_%ED%95%99%EC%8A%B5%EC%A0%95%EB%A6%AC.ipynb)
[머신러닝 총정리](https://github.com/Kim-JungHyun01/AIStudy24/blob/master/%EC%A0%95%EB%A6%AC/%EB%A8%B8%EC%8B%A0%EB%9F%AC%EB%8B%9D%EC%B4%9D%EC%A0%95%EB%A6%AC.ipynb)

---
머신러닝
---
**시나리오 1**

- 학습시간 : 2024-12-30 ~ 2024-12-31

- MBC 상점에서 앱마켓을 운영하는데 AI를 활용하는 기법을 학습해보자

    1단계) 앱마켓에서 살아있는 생선을 팔기 시작했다.

    2단계) 물류센터에서 생선을 고르는 직원이 있는데 생선이름을 외우지 못한다.

    3단계) 생선의 종류 : 도미, 곰들메기, 농어, 강꼬치고기, 빙어, 송어등등

    4단계) AI 미션 : 생선의 길이가 30cm이상이면 '도미'
  
- k-최근접 분류 알고리즘

  1. [머신러닝_생선길이학습](https://github.com/Kim-JungHyun01/AIStudy24/blob/master/%ED%85%8C%EC%8A%A4%ED%8A%B8/%EB%A8%B8%EC%8B%A0%EB%9F%AC%EB%8B%9D_%EC%83%9D%EC%84%A0%EA%B8%B8%EC%9D%B4%ED%95%99%EC%8A%B5.ipynb)
  2. [훈련세트 & 테스트세트](https://github.com/Kim-JungHyun01/AIStudy24/blob/master/%ED%85%8C%EC%8A%A4%ED%8A%B8/%ED%9B%88%EB%A0%A8%EC%84%B8%ED%8A%B8_%ED%85%8C%EC%8A%A4%ED%8A%B8%EC%84%B8%ED%8A%B8.ipynb)
  3. [데이터전처리학습](https://github.com/Kim-JungHyun01/AIStudy24/blob/master/%ED%85%8C%EC%8A%A4%ED%8A%B8/%EB%8D%B0%EC%9D%B4%ED%84%B0%EC%A0%84%EC%B2%98%EB%A6%AC%ED%95%99%EC%8A%B5.ipynb)
---
**시나리오 2**

- 학습시간 : 2024-12-31 ~ 2025-01-02

- 시기 : 여름 농어철

    농어주문이 크게 늘어남 => 무게단위로 판매하기로 결정

    이유 : 가격측정 원활 및 소비자들의 불만 완화

    단, 공급처에서 생선무게를 잘못 측정할 수도 있음
  
- k-최근접 회귀 알고리즘
  
    1. [이웃회귀](https://github.com/Kim-JungHyun01/AIStudy24/blob/master/%ED%85%8C%EC%8A%A4%ED%8A%B8/%EC%9D%B4%EC%9B%83%ED%9A%8C%EA%B7%80.ipynb)
       
- 선형회귀, 다항회귀
    1. [k-최근접 이웃 알고리즘의 한계](https://github.com/Kim-JungHyun01/AIStudy24/blob/master/%ED%85%8C%EC%8A%A4%ED%8A%B8/k_%EC%B5%9C%EA%B7%BC%EC%A0%91_%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98_%ED%95%9C%EA%B3%84.ipynb)

- 특성공학
    1. [다중회귀](https://github.com/Kim-JungHyun01/AIStudy24/blob/master/%ED%85%8C%EC%8A%A4%ED%8A%B8/%EB%8B%A4%EC%A4%91%ED%9A%8C%EA%B7%80.ipynb)

---
**시나리오 3**

- 학습시간 : 2025-01-03 ~ 2025-01-06

- 럭키백 판매

  구성품 : 생선(종류 7가지 랜덤)

  7가지의 생선 각각의 뽑기확률 제공

  1. [로지스틱회귀](https://github.com/Kim-JungHyun01/AIStudy24/blob/master/%ED%85%8C%EC%8A%A4%ED%8A%B8/%EB%A1%9C%EC%A7%80%EC%8A%A4%ED%8B%B1%ED%9A%8C%EA%B7%80_%EC%86%8C%ED%94%84%ED%8A%B8%EB%A7%A5%EC%8A%A4.ipynb)
  2. [확률적경사하강법](https://github.com/Kim-JungHyun01/AIStudy24/blob/master/%ED%85%8C%EC%8A%A4%ED%8A%B8/%ED%99%95%EB%A5%A0%EC%A0%81%EA%B2%BD%EC%82%AC%ED%95%98%EA%B0%95%EB%B2%95.ipynb)
---
**시나리오 4**
- 학습시간 : 2025-01-06 ~ 2025-01-07
- 신상품 : 캔 와인
  
  주류는 온라인 판매가 안되기에 온라인 예약 후, 오프라인매장에서 구매유도
  
  근데, 입고된 와인이 레드 or 화이트인지 구분표시가 안되있음
  
  캔에 인쇄된 라벨정보 : 알콜도수, 당도, pH 값(alcohol,sugar,pH,class)
  
  품질확인용으로 개방한 캔 : 테스트용

  1. [결정트리](https://github.com/Kim-JungHyun01/AIStudy24/blob/master/%ED%85%8C%EC%8A%A4%ED%8A%B8/%EA%B2%B0%EC%A0%95%ED%8A%B8%EB%A6%AC.ipynb)
  2. [교차검증](https://github.com/Kim-JungHyun01/AIStudy24/blob/master/%ED%85%8C%EC%8A%A4%ED%8A%B8/%EA%B5%90%EC%B0%A8%EA%B2%80%EC%A6%9D_%EA%B7%B8%EB%A6%AC%EB%93%9C%EC%84%9C%EC%B9%98.ipynb)
  3. [앙상블](https://github.com/Kim-JungHyun01/AIStudy24/blob/master/%ED%85%8C%EC%8A%A4%ED%8A%B8/%EC%95%99%EC%83%81%EB%B8%94.ipynb)

---
딥러닝
---
**시나리오 1**
- 학습시간 : 2025-01-07 ~ 2025-01-08
- 본인이 구매한 과일사진을 홈페이지에 업로드하면 추첨을 하여 상품을 제공
  고객이 올린 사진을 학습하여 과일 분류

  1. [비지도학습, 군집알고리즘](https://github.com/Kim-JungHyun01/AIStudy24/blob/master/%EB%94%A5%EB%9F%AC%EB%8B%9D/%EA%B5%B0%EC%A7%91%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98.ipynb)
  2. [k-평균(k-mean)](https://github.com/Kim-JungHyun01/AIStudy24/blob/master/%EB%94%A5%EB%9F%AC%EB%8B%9D/k_%ED%8F%89%EA%B7%A0(k_means).ipynb)
  3. [주성분분석(PCA)](https://github.com/Kim-JungHyun01/AIStudy24/blob/master/%EB%94%A5%EB%9F%AC%EB%8B%9D/%EC%A3%BC%EC%84%B1%EB%B6%84%EB%B6%84%EC%84%9D.ipynb)

---

**시나리오 2**
- 학습시간 : 2025-01-09~
- 럭키백을 패션분야에 접목
  상품갯수 증가 및 일반 잡화용제공

  1. [인공신경망](https://github.com/Kim-JungHyun01/AIStudy24/blob/master/%EB%94%A5%EB%9F%AC%EB%8B%9D/%EC%9D%B8%EA%B3%B5%EC%8B%A0%EA%B2%BD%EB%A7%9D.ipynb)
---
