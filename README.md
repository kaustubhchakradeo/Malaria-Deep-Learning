# Malaria-Deep-Learning

This repository documents research work done towards detection of Malaria on thin smears, using Deep Learning.
The author(s) use different existing deep learning models like VGG, AlexNet, ResNet, and create new hybrid models to detect malaria.
You can download the dataset here- https://lhncbc.nlm.nih.gov/publication/pub9932

All work was done using-
Ubuntu 18.04 OS.
GPU- NVIDIA GTX1660t
Driver Version 440.33.01
Cuda Version 10.2
Tensorflow Version 2.0.0

----------------------------------------------------------------------------------------------------------------------------
MalariaLeakyReLU.ipnb


Modified VGG model with a Leaky ReLU achieved

Train accuracy of 99.22%
Test accuracy of 96.34%

                precision    recall  f1-score   support

           0       0.95      0.97      0.96      2743
           1       0.97      0.95      0.96      2769
accuracy                               0.96      5512
macro avg          0.96      0.96      0.96      5512
weighted avg       0.96      0.96      0.96      5512

Confusion Matrix: 
 2669   74
 128    2641
 
Sensitivity: 0.973022 
Specificity: 0.953774 


