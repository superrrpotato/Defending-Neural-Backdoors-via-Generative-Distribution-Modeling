# Defending-Neural-Backdoors-via-Generative-Distribution-Modeling
The code is for our NeurIPS 2019 paper: https://arxiv.org/abs/1910.04749

# Experiment
All the experiment we did in our paper are included in the class Experiments()
    
## test_contour: 
 An overall PCA result following by several figure with different beta value is plotted

## test_alpha: 
 An overall PCA result following by several figure with different alpha value is plotted

## detect_cifar: 
 Only the class been attacked exists valid trigger (You will see ASR~90%). Other classes' ASR are all very low.

## defend_cifar_10_all
 test defense on cifar_10 dataset

## defend_cifar_100_all
 test defense on cifar_100 dataset

## defend_cifar_10_all_ensemble
 test defense on cifar_10 dataset using ensemble model

## defend_cifar_100_all_ensemble
 test defense on cifar_100 dataset using ensemble model

## point_defend_cifar_10
 baseline method on cifar-10

## point_defend_cifar_100
 baseline method on cifar-100
