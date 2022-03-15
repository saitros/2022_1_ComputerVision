# Densely connected convolutional networks

## Introduction

이 연구에서 근본적으로 해결하고자 했던 내용은 

> ‘As information passes through many layers, it can vanish and “wash out” by the time it reaches the end (or beginning) of the nework’

네트워크가 깊어질수록 정보가 처음이나 끝에 도달할때 사라지거나 "wash out" 씻겨나갈 수 있다는 부분이다. 

관련된 연구들은 공통적으로 앞쪽 레이어를 뒤쪽 레이어와 연결시키고자 하였다.

>Although these different approaches vary in network topology and training procedure, they all share a key characteristic: they create short paths from early layers to later layers

## Method

## Experiment

## Summary

(발표듣기전) ResNet과 유사한 구조를 가지고 있지만 previous layer 의 정보를 concatenation 하는 부분에서 차이가 벌어진다.
previous layer 의 정보를 concat 함으로써 next layer 에 정달되는 정보의 receptive field 가 다양해지고, 반복되는 학습(? previous layer 가 여러번 등장하는)으로 중간 layer 가 discriminative
한 특징을 가질 수 있게한다.
이러한 방식을 통해서 DenseNet 은 Model compactness, Feature Reuse 면에서 좋은 성과를 보임으로써 작고 효율적인 구조를 제안한다.

