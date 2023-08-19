# Foreign-Paper-3
### 발행처: Journal of Econometrics
### 발행날짜: 2019
### 제목: Autoencoder asset pricing models

### What is the main research question of the study?
   
1) 일반적인 Autoencoder보다 Conditional Auto Encoder이 자산배분 전략에 효과적이다.
   
### What research methodology did the authors employ?
   
1) 딥러닝의 Conditional Auto Encoder 기법을 적용한다.
   
   일반적인 오토인코더와는 달리 Conditional AutoEncoder은 종가 또는 수익률 변수를 고려하되 데이터 셋의 다른 변수(거래량 추이, 외국인보유 수 등)을 함꼐 고려하여 만들어 
   진 모델이기 때문에 데이터의 활용성이 더 높다.
   
2) 과거의 문헌들은 특정 이유(저가 주식, 회귀한 주식)로 종목의 필터링 과정을 진행시켰지만 Conditional AutoEncoder 모델은 우수한 능력 덕분에 별다른 필터를 하지 않았다.
    
### What were the main findings of the study?

1) Conditional AutoEncoder이 PCA(IPCA 포함) 그리고 전통적인 AutoEncoder보다 성능이 더 좋다.

### Did the authors provide appropriate support for their conclusions?

1) R^2과 shapre ratio을 이용하여 PCA, IPCA 그리고 Conditional AutoEncoder의 성능을 평가하고 있다..

### What is the significance or importance of this study?

1) 3가지의 특성 범주가 영향력이 있다고 판단하였다. 첫번째는 가격트렌드 범주로 여기에는 단기반전, 주식모멘텀, 모멘텀 변화, 산업모멘텀, 최근수익 및 장기반전을 포함한다. 두번째 범주에는 유동성변수인 거래 회전율 및 거래 회전율 변동성, 로그 시장 자본, 거래금액, 제로거래일수, 매수-매도 스프레드가 포함된다. 마지막으로는 리스크 지표로 수익변동성, 시장베타이다.

2) 다른 논문의 수익률 예측 모델을은 다양한 가정(리스크-수익 트레이드오프 혹은 리스크 노출에 대한 수익률 알파)간에 구분을 두지 않는다. 하지만 이 모델은 모든 리스크 요인 노출을 통해서 전달되도록 한다. 또한 무위험 차익거래의 경제적 제한도 부과한다.
   
3) 샤프 ratio 성과기반으로 보면 Conditional AutoEncoder이 1.53이고 두번째로 높은 IPCA가 0.96으로 계산되었다.

### What are the potential limitations of this study?

1) 60년치의 데이터를 이용했기 때문에 최근 주식시장의 흐름과 다소 동떨어질 수도 있다.(개인적인 생각)
