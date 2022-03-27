# Model-Agnostic Meta-Learning for Fast Adaptation of Deep Networks

Keyword : meta learning, optimization-based methods, model-agnostic meta-learning(MAML), Fast adapation

## Introduction

Artifical agents는 인간 지능과 같이 몇개의 샘플을 통해서 빠르게 배워나가야한다

본 연구에서 제안하고자 하는 모델인 MAML은 Gradient Descent procedure 로 학습하는 문제에 적용이 가능하고, 인간 지능과 같이 적은 데이터만으로 사람이 배우듯 
모델이 학습하는 것 이다.

연구의 가장 큰 contribution 은 다음과 같다. 

- Initial Parameter가 몇 번의 업데이트 만으로 maximal performance를 발휘하도록 학습

- 기존의 연구들과는 달리, 특정 모델 구조에 한정적이거나 parameter를 늘리거나 하지 않는다
