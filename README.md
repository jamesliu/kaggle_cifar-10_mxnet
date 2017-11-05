# kaggle_cifar-10_mxnet
### abstract
kaggle CIFAR10 competition code, implement by mxnet gluon.</br>
The current score is better than the best one ranked in Kaggle Public Leaderboard(0.9553)：
![](submission.png)

### methods
Train neural networks individually(densenet and resnet) and ensemble them. It could be further improved by adding more networks.

### files
file | description
--- | ---
train.ipynb | Ensemble models 
train_resnet.ipynb | Train resnet
train_densenet.ipynb | Train densenet
