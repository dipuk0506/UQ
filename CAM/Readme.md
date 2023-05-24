# Reduction of Class Activation Uncertainty with Background Information

Abstract: Multitask learning is a popular approach to training high-performing neural networks with improved generalization. In this paper, we propose a background class to achieve improved generalization at a lower computation compared to multitask learning to help researchers and organizations with limited computation power. We also present a methodology for selecting background images and discuss potential future improvements. We apply our approach to several datasets and achieved improved generalization with much lower computation. We also investigate class activation mappings (CAMs) of the trained model and observed the tendency towards looking at a bigger picture in a few class classification problems with the proposed model training methodology.

<img src="https://github.com/dipuk0506/UQ/blob/main/CAM/CAM_bird_.png" width="700">
Fig. Models with both traditional training and training with background class are applied to a bird image (a) in the STL-10 dataset. Subplots (b) and (c) show class activation mapping of the bird class on the final convolutional layer respectively for traditional and for training with background situations. Subplots (d) and (e) show class activation mapping with the image. Subplots (f) and (g) show deep feature factorization results on the image for the traditional and proposed method respectively.

### Link to paper: https://arxiv.org/abs/2305.03238


#### According to our literature search, we received new state-of-the-art performance in the STL-10, CIFAR-10, CIFAR-100, Caltech-101, CINIC-10 datasets on May 2023. The link to the Kaggle notebook with execution details is as follows: 

##### We claimed Oxford-102 SOTA in v2 of the paper. After more search, we observed that we got the second-best performance in the Oxford-102 dataset.  

1. STL-10: https://www.kaggle.com/code/dipuk0506/stl-10-with-background/notebook
2. CIFAR-10: https://www.kaggle.com/code/dipuk0506/cifar10-with-background-spinalnet
3. CIFAR-100: https://www.kaggle.com/code/sadiakhanam7/cifr100-transformer-background-spinalnet
4. Oxford-102: https://www.kaggle.com/code/dipuk0506/oxford102-with-background
5. Caltech-101: https://www.kaggle.com/code/dipuk0506/caltech101-transformer-background
6. CINIC-10: https://www.kaggle.com/code/sadiakhanam7/cinic-10-transformer-background

