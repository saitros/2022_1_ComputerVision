# Decoupled Weight Decay Regularization

AdamW 로 알려진 논문

SGD 의 경우 weight decay 를 위해 L2 regularization 을 사용하지만, Adam 의 경우 똑같이 적용할 수 없다.
--> 뒤에 관련된 내용이 나오겠지

Adam 이 좋은 성능을 보임에도 불구하고 몇몇 경우에서 SGD with momentum 이 좋은 성능을 보일 때도 있었고, 관련하여
다양한 가설을 가진 연구들이 있었기에 weight decay 에 대한 연구를 진행합니다.

## Observation about Adam

### L2 regularization and weight decay are not identical

### L2 regularization is not effective in Adam

### Weight decay is equally effective in both SGD and Adam.

### Optimal weight decay depends on the total number of batch passes/weight updates.

### Adam can substantially benefit from a scheduled learning rate multiplier.

