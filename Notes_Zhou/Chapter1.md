# 第一章 绪论

## 1.1 引言
> 略过

## 1.2 基础术语
> 这部分的内容有点多，有些需要有对应的数学基础或概念。我只是做了简单的解释，对我复习回看比较有用，但是如果第一次看，还是看书比较好。周志华老师用西瓜做了比喻，非常易懂。

数据集（data set）：一组记录

示例（instance） 或 样本（sample）：一条记录

属性（atribute）或特征（feature）：在某方面的表现或性质的事项

属性值（attribute value）：属性取值

属性空间（attribute space）或样本空间（sample space）或输入空间（input space）：所有属性的集合

特征向量（feature vector）：书中的示例很形象，在一个三维坐标系里，x，y，z三轴分别代表三个属性，那么一个样本在坐标系中的位置相对坐标系原点就会有一个坐标向量，这个坐标向量就是特征向量，其实也就代表了对应的这个样本

样本的维数（dimensionality）：样本属性的个数

学习（learning）或训练（training）：学得模型的过程

训练数据（training data）：训练过程使用的数据

训练样本（training sample）：训练使用的每一个样本

训练集（training set）；训练样本的集合。（个人理解：和训练数据不同的地方在于，训练集强调的是样本集合，而训练数据强调的是数据，一个样本的一个属性就叫数据，目标更小）

假设（hypothesis）：模型学到的规律

真相（ground-truth）：数据真正的规律

学习器（learner）：模型

预测（prediction）：通过算法进行判断

标记（label）：关于示例结果的信息

样例（example）：拥有标记信息的示例或样本

标记空间（label space）或输出空间（output space）：标记的集合

分类（classification）：预测结果是离散的

回归（regression）：预测结果都是连续的

二分类（binary classification）：分类类别只有两个

正类（positive class）

反类（negative class）

多分类（multi-class classification）

测试（testing）：测试模型预测的结果是不是正确

测试样本（testing sample）：用来测试的样本

聚类（clustering）：将训练集分组（跟分类不同的是，这些组事先并不知道）

簇（cluster）：聚类分出来的每一个组

监督学习（supervised learning）：拥有标记信息（分类和回归）

无监督学习（unsupervised learning）：没有标记讯息（聚类）

泛化（generalization）：学得模型适用于新样本

分布（distribution）：全体样本服从一定的规律，比如正态分布（概率论基础）

独立同分布（independent and identicallly distributed）：每个样本服从同样的分布，而且是独立地从这个分布上采样出来的

## 1.3 假设空间
归纳（induction）：从具体的事实归结出一般性规律。“从样例中学习”即归纳学习（inductive learning）。

假设空间：所有假设组成的空间

版本空间：与有限的训练集匹配的假设集合

## 1.4 归纳偏好
可能存在多个假设匹配训练集，机器学习算法在学习过程中对某种类型假设的偏好，称为归纳偏好（inductive bias）。

任何一个有效的机器学习算法必有其归纳偏好。

如何选择偏好呢？“奥卡姆剃刀（Occam's razor）”是一种常用的、自然科学研究中最基本的原则，即“若有多个假设与观察一致，则选最简单的那个”。但这并不是黄金法则，对于一个学习算法A，如果它在某些问题上比学习算法B好，那么必然存在另一些问题，在那里B比A好。

没有免费的午餐定理（No Free Lunch Theorem，简称NFL定理）。最重要的寓意，具体问题具体分析，不要空谈什么算法更好，毫无意义。

## 1.5 发展历程
> 略过

## 1.6 应用现状
> 略过


