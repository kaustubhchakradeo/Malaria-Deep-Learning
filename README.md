# Malaria-Deep-Learning

Malaria is a serious disease which affects hundredsof millions of people around the world, each year. If not treatedin time, it can be fatal. Despite of recent developments in malariadiagnostics,   the   microscopy   method   to   detect   malaria   staysthe  most  common.  Unfortunately,  the  accuracy  of  microscopicdiagnostics is dependent on the skill of the microscopist and limitsthe  throughput  of  diagnosing  malaria. Using deep learning methods to detect malaria helps in increasing the accuracy and reduce costs required for detection. This repository documents research work done towards detection of Malaria on thin smears, using Deep Learning.
We used different existing deep learning models like VGG, AlexNet, ResNet, and our own CNN model to detect malaria on thin smears. Our CNN outperformed the pretrained models and the models used in existing literature. The  dataset  was  taken  from  the  Lister  Hill  National  Cen-tre  for  Biomedical  Communications  —  National  Library  ofMedicine. The dataset is divided into two folders, Parasitized, and  Uninfected,  each  containing 13,779 images. You can download the dataset here- https://lhncbc.nlm.nih.gov/publication/pub9932. We found that some images in the dataset were mislabeled,  poorly  segmented,  or contained impurities. These were labelled correctly or removed in some cases. You can download the improved dataset here- INSERT LINK HERE.

All work was done using-
Ubuntu 18.04 OS
CPU- Intel Core i5 9300H @2,40GHz with 16 GB RAM
GPU- NVIDIA GTX1660t with 6 GB RAM
Driver Version 440.33.01
Cuda Version 10.2
Tensorflow Version 2.0.0 with cuDNN 7.1
Python 3.8.6 with Keras 2.1.1
Jupyter Notebook version 6.0.3

----------------------------------------------------------------------------------------------------------------------------
MalariaLeakyReLU.ipnb


Our CNN architecture achieved: 

Train accuracy of 99.67%

Test accuracy of 98.22%

                precision    recall  f1-score   

           0       0.99      0.98      0.98      
           1       0.98      0.99      0.98     
           


Confusion Matrix: 

  [[TP = 2401   FP = 57]
  
 [ FN = 36 TN = 2746]]
 
Sensitivity: 0.9768 

Specificity: 0.9871 

----------------------------------------------------------------------------------------------------------------------------------

![Results](../master/PLOTS/Table_Results.png)
Results comparison with other literature

