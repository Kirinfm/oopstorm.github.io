---
layout: pages
title: Tensorflow：实战Google深度学习框架
date: 2018.11.05
tags: Tensorflow 深度学习
---
- 深度学习简介
- TensorFlow 环境搭建
- TensorFlow 入门
- 深层神经网络
- MNIST 数字识别问题
- 图像识别与卷积神经网络
- 图像数据处理
- 循环神经网络
- TensorBoard 可视化
- TensorFlow 计算加速

# 深度学习简介
输入->基础特征->特殊特征->权重->预测

如搜狗输入法中文输入 ten

ten 为输入，基础特征是`中文拼音`，特殊特征为`读音`、`中文喜好(经常使用的中文)`、`拼音截取(te'n/t'en)`等作为特殊特征，按照权重进行预测分布。
![图片1](/assets/2018-11-05-tensorflow实战/img1.png)

> 为构思的输入预测，并未阅读搜狗输入法源码，并不确定是输入法真实的实现方式


# 计算图
Tensor （张量）=》 多维数组

张量即描述事物的多维数组，二维数组能够描述一条线，三维数组能够描述线以及线的角度，多维数组能够描述各种特征。

Flow（流）

![神经网络传递](/assets/2018-11-05-tensorflow实战/img2.png)

![神经网络传递](/assets/2018-11-05-tensorflow实战/img3.png)

# 深层神经网络
损失函数 >0.5 => 1 <0.5 => 0   预测
（梯度下降算法 
反向传播算法）  真实

# MNIST 数字识别问题
mnist 手写体数字识别数据集
包含60000个训练数据及10000个测试数据，可分为10类

# 图像识别与卷积神经网络CNN
图像数据处理
循环神经网络
