### 神经网络与深度学习（译）

> 本项目包含了 [这里](http://neuralnetworksanddeeplearning.com) 的所有内容，包括原文作者（[Michael Nielsen](http://michaelnielsen.org/)）整理的读者常见问题，附录等。

### Index

1. 前言
2. 这本书是关于什么的？
3. 关于练习和问题
4. 第一章 - 使用神经网络识别手写数字
   1. 感知机
   2. S 型神经元
   3. 神经网络架构
   4. 一个简单的分类手写数字的网格
   5. 使用梯度下降算法进行学习
   6. 迈向深度学习
5. 第二章 - 反向传播算法如何工作
   1. 热身：神经网络中使用矩阵算法快速计算输出的算法
   2. 关于代价函数的两个假设
   3. Hadamard 乘积，s ⊙ t
   4. 反向传播的四个基本方程
   5. 四个基本方法的证明（可选）
   6. 反向传播算法
   7. 代码
   8. 在哪种层面上，反向传播算法是最快的的算法？
   9. 反向传播：全局观
6. 第三章 - 改变神经网络的学习方法
   1. 交叉熵代价函数
      1. 引入交叉熵代价函数
      2. 使用交叉熵来对 MNIST 数字进行分类
      3. 交叉熵的含义？源自哪里？
      4. 柔性最大值
   2. 过度拟合与规范化
      1. 规范化
      2. 为何规范化可以帮助减轻过度拟合
      3. 规范化的其他技术
   3. 权重初始化
   4. 再看手写识别问题：代码
   5. 如何选择神经网络的超参数
   6. 其他技术
      1. 随机梯度下降的变化形式
      2. 人工神经元的其他模型
      3. 有关神经网络的故事
7. 第四章 - 神经网络可以计算任何函数的可视化证明
   1. 两个预先声明
   2. 一个输入和一个输出的普遍性
   3. 多个输入变量
   4. S 型神经元的延伸
   5. 修补阶跃函数
   6. 结论
8. 第五章 - 深度神经网络为何很难训练
   1. 消失的梯度问题
   2. 什么导致了消失的梯度问题？深度神经网络中的梯度不稳定性
   3. 在更加复杂网络中的不稳定梯度
   4. 其他深度学习的障碍
9. 第六章 - 深度学习
   1. 介绍卷积网络
   2. 卷积神经网络在实际中的应用
   3. 卷积网络的代码
   4. 图像识别领域中的近期发展
   5. 其他的深度学习模型
   6. 神经网络的未来
10. 附录：是否有一个关于智能的简单算法？
11. 致谢
12. FAQ

### Auther
In academic work, please cite this book as: Michael A. Nielsen,"Neural Networks and Deep Learning", Determination Press, 2015

This work is licensed under a Creative Commons Attribution-NonCommercial 3.0 Unported **License**. This means you're free to copy, share, and build on this book, but not to sell it. If you're interested in commercial use, please contact me.

### Translator
[临书](https://github.com/tmpbook)：之前校对过一篇文章，叫《我是如何在谷歌做开发者用户体验的》，我觉得角度很特别，作者讲解了如何提升开发者（而不是用户）的用户体验，本文我会试着加一些注解，希望看完本翻译项目的开发者们**提高识别能力而非回忆**，当然你觉得这本书哪里读起来不顺畅请尽管提出来。

如果太久没更，请麻烦你用 issue 呼一下我。最后，所有内容有疑问请随意提 PR（包括本 README.md）

### 其他完整翻译

- [zhanggyb/nndl](https://github.com/zhanggyb/nndl)
