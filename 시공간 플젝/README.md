## 시공간 통계 수업 최종 프로젝트



### 프로젝트에 대해

시공간 통계 수업의 최종 프로젝트 결과입니다. 시공간 통계에서 흔히 발생하는 고차원 자료에 대한 추론 방법을 조사하는 것이 주제입니다. 



### 프로젝트를 하게된 동기

시공간 통계는 관측 데이터 각각에 대해서 모수를 가정하기 때문에 관측 데이터가 조금만 많아져도 고차원 자료가 되어서 추론 방법이 달라집니다. 예를 들어, 데이터가 10000개라면 관련 모수도 10000개를 가정하는데 이에 대해서 깁스 샘플링을 돌린다면, 평생 끝나지 않을 수도 있습니다. 따라서 관련 방법이 많이 개발되었고 이 방법들을 익혀서 나중에 실질적으로 고차원 문제에 직면했을 때 효과적으로 문제를 해결하고 싶었습니다.



### 사용 기술

* R



### 프로젝트에 대한 요약

총 4가지 방법을 리뷰했습니다.

* Hierarchical Nearest Neighbor Gaussian Process [spNNGP package]
* Predictive Process Model [spBayes package]
* Stochastic Partial Differential Equation [INLA package]
* Fixed Rank Kriggng [FRK package]

위 네가지 방법에 대해서 논문 리딩을 하고, 구현된 R 패키지와 시공간 데이터를 이용하여 Experiments 진행하였습니다. 네 방법을  krigging (prediction 결과)에 대한 MSE / MAE / CRPS의 척도를 구하여 비교하였습니다.



### 자세한 프로젝트 내용



