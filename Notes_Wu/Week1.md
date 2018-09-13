# 吴恩达 - 机器学习

## Welcome

## Introduction

#### What is Machine Learning?

New definition

- E: Experience
- T: Task
- P: Performance measure

Two types:
- Supervised learning
- Unsupervised learning

other types: reinforcement learning, recommender system

#### Supervised Learning

"right answer" is given in the data set.

- Regression: predict continuous valued output
- Classification: predict discrete valued output

#### Unsupervised Learning

No "right answer" is given in the data set.

Octave: free open source

## Model and Cost Function

#### Model Representation

Notation:

- m = Number of training examples
- x = input variable/features
- y = output variable/target variable

Training Set

Learning Algorithm

h: hypothesis

#### Cost Function
definition of the cost function and our target is to minimize the cost function

#### Cost Function - Intuition I
"the plot of the hypothesis" vs "the plot of the cost function"

#### Cost Function - Intuition II
contour plots of the cost function

## Parameter Learning

#### Gradient Descent

梯度下降法

概要（Outline）:

梯度下降有可能收敛到局部最优解。

应用梯度下降法解决线性回归问题：线性回归问题都是凸函数，意味着cost function只有一个global的最优解。不用担心局部最优。


## Linear Algebra Review

主要讲：

1. 矩阵，向量，标量的定义。
- 加减， 标量乘法
- 矩阵（向量）乘法
- 矩阵乘法的性质（不支持交换律，支持结合律，单位矩阵）
- 矩阵操作（逆矩阵，矩阵转置）

> 学过线性代数的就不用看了，都是些基础
