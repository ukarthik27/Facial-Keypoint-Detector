# Facial-Keypoint Detector using CNN
Goal : Identify facial keypoints using CNNs which can part of a CV pipeline in emotion analysis, AR applications using CNN

Approach: 
1. Constructed a Deep CNN with Batch Norm in the inital Conv layers. Used ReLu activation function with dropout to keep a check overfitting.
2. Added Residual Block (ResNet) to propogate and update features deep into NN.
3. Optimizer : Adam, to deal with sparse gradients. Loss function:  mean squared error 

<br />

<!-- ![alt text](https://github.com/ku2045/NYU-RM-/blob/main/yolo_op1.png?raw=true) -->
