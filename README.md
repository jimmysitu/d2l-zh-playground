# d2l-zh-playground
JM's d2l playground

## 数据集
数据集都放在`data`目录下，包括Kaggle比赛的训练数据和测试数据。

## 实战Kaggle比赛：预测房价
Notebook `pytorch/chapter_multilayer-perceptrons/kaggle-house-price.ipynb`


## 实战Kaggle比赛：树叶分类
Notebook `pytorch/chapter_convolutional-modern/kaggle-classify-leaves.ipynb`

### 训练调参笔记
- 观察训练样本，可以发现树叶的背景比较统一，通常会有单色的背景纸
- 树叶是没有方向的，所以可以做较多的旋转增强
- 树叶可能是不对称的，所以不适合做翻转增强

## 实战Kaggle比赛：图像分类（CIFAR-10）


## 实战Kaggle比赛：狗的品种识别（ImageNet Dogs）