# 机器学习基础知识
## 什么是机器学习
机器学习就是通过输入大量的学习资料，然后让机器学习算法通过数据集来训练模型，然后有了新的样本之后，通过这个模型来获取输出结果。

![](https://ws3.sinaimg.cn/large/006tNbRwgy1fusvyluvy4j31820hyq7u.jpg)

## 机器学习中的数据
机器学习训练模型需要大量的数据。

+ 数据整体叫数据集
+ 每一行数据称为一个样本
+ 除最后一列，每一列表达样本的一个特征
+ 最后一列，称为标记

## 机器学习的基本任务
机器学习的基本任务分为两类：分类任务和回归任务。

分类任务分为：

+ 二分类任务：例如判断邮件是垃圾邮件还是不是垃圾邮件，二选一。
+ 多分类任务：例如手写数字识别，在多个数字中选出一个识别，还有图像识别等等。
+ 多标签分类任务

回归任务：特点是结果是一个连续数字的值，而非一个类别。例如房屋价格、市场分析等。

## 机器学习方法
机器学习方法的分类主要分为以下几类：

+ 监督学习
+ 非监督学习
+ 半监督学习
+ 增强学习

## 监督学习
监督学习是给机器的训练数据拥有标记或者答案的数据集。相关算法如下：

+ K近邻
+ 线性回归和多项式回归
+ 逻辑回归
+ SVM
+ 决策树和随机森林

## 非监督学习
非监督学习是给机器的训练数据没有任何标记或答案的数据集，对没有标记的数据进行分类-聚类分析。

### 非监督学习的意义
对数据进行降维处理，主要包含两方面内容：

+ 特征提取：当我们面对一些数据的时候，数据有很多的特征，其中一些的特征对我们的数据是没有联系的。
+ 特征压缩：不扔掉任何的特征，有的时候特征的关联性特别的强。