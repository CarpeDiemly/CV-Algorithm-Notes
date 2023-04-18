# CV-Algorithm-Interviews-Notes

**起始日期：2021-12.05 — offer**

先说下本人情况：双非研究生 + 旷视实习 + 顶会非核心作者 + 几段项目经历 目前上岸一家芯片公司的算法研究员岗位！

秋招过程总结就是：海投 海投 海投！总之就是非常漫长，好在坚持下来了吧，也汇总了一些准备的笔记，希望对大家有所帮助！

本仓库汇总CV算法岗重要的一些知识点和面试问答，主要分为**基础篇**包括`数据结构`、`计算机视觉`、`机器学习`、`图像处理`和`Python及C++`基础 五大块，还有**实战篇**包括：`简历准备`、`项目介绍`、`面经汇总`等。

为了刺激下大家的神经，激发斗志，在往下看之前可以先看看这篇经验分享：[算法岗必须人手一篇顶会？超详细面经：无论文、无实习拿下腾讯CV算法岗](https://mp.weixin.qq.com/s?__biz=MzI5MDUyMDIxNA==&mid=2247494712&idx=1&sn=2c906e0c4062955adb8bf4bbda7cb1a8&chksm=ec1c01c1db6b88d7e1f4b8ff2b2f084d1e7961ffdcb29c9de03328cb9c2a14fe68522b7b0c2f&mpshare=1&scene=1&srcid=&sharer_sharetime=1588779616413&sharer_shareid=40621009b5a320f1873da9d6e9a820a7#rd)。创建本仓库的灵感也就是来源于此文，感谢大佬的分享，同时感谢该[CV_interviews_Q-A](https://github.com/GYee/CV_interviews_Q-A)仓库作者，很多知识都是按照他的来的，而且内容组织十分nice，站在他们的肩膀上，添加自己的思路和想法，力争满足秋招面试需求！（也希望大家在备战过程中，逐步形成自己的知识系统，这也许是本仓库最大的意义所在！）

## 使用方法

由于github上直接看的话很多公式和图片看不了，**请 clone 到本地然后下载安装Typora查看**，Typora 完全免费，体验非常好，强烈安利一波。

知识不是看几遍就会的，好记性不如烂笔头，最好看了我们的总结后，你也自己敲出一个适合你的版本，或删减或添加或修改为适合你的表达方式，这样会大大提升学习的效果。

**需要声明的一点是**：本文是作为个人学习总结的，不生产知识，只是知识的搬运工，主要做的工作是知识整合与逻辑梳理，参考了很多大神的博客及文章资料(文章中会注明参考的资料，感谢这些作者的贡献)，当然也会有自己的思考，不喜勿喷，如有错误，恳请指正！

## 知识点清单

PS：这里列出各大块的问题部分清单，详细内容请查看对应于各文件夹下的md文件。

### leetcode

由于内容太杂，主要放在notion上进行统一管理，链接见此处：[【notion传送门】](https://continuous-lettuce-a13.notion.site/f66f1ad4f89146d1baf216155172416e)

### 图像处理

主要是传统图像处理，涉及图像滤波、边缘检测、特征提取等，采用数学方式对图像的空间域以及频域进行操作，可谓图像入门的基石！

| 序号 | 是否完成 |                问题描述                 |
| :--: | :------: | :-------------------------------------: |
|  1   |    是    | 01_边缘检测算子有哪些以及它们之间的对比 |
|  2   |    是    |           02_Laplace算子专讲            |
|  3   |    是    |            03_开操作与闭操作            |
|  4   |    是    |        04_常见的三种图像插值方法        |
|  5   |     是     |     05_Hough变换检测直线与圆的原理      |
|  6   |    是    |            06_LBP算法原理           |
|  7   |    是    |        07_HOG算法原理     |
|  8   |     是     |     08_FAST、BRIEF、ORB算法原理      |
|  9   |    是    |        09_SIFT算法原理     |
|  10   |     是     |     10_传统特征提取方法总结      |
|  11   |     是     |     11_旋转矩阵    |

### 深度学习

本质还是一种特征提取基础，本章节内容侧重于卷积原理、损失函数、反向传播原理等通用的基础知识。

| 序号 | 是否完成 |                问题描述                 |
| :--: | :------: | :-------------------------------------: |
|  1   |    是    | 01_三种常见的激活函数 |
|  2   |    是    |          02_过拟合和欠拟合的表现与解决方法            |
|  3   |    是    |           03_代码实现卷积操作           |
|  4   |    是    |       04_BN层的深入理解        |
|  5   |    是    |           05_ReLU函数在0处不可导，为什么还能用          |
|  6   |    是    |       06_Pooling层的作用以及如何进行反向传播     |
|  7   |     是     |     07_梯度消失和爆炸以及解决方法      |
|  8   |    是    |       08_softmax函数及求导过程     |
|  9   |     是     |     09_为什么输入网络前要对图像做归一化      |
|  10   |     是     |  10_优化器原理及发展路线  |
| 11 | 是 | CNN网络各种层的FLOPs和参数量paras计算 |
| 12 | 是 | CNN在图像上表现好的原因 |
| 13 | 是 | 感受野大小的计算问题 |
| 14 | 是 | 卷积网络中的卷积与互相关的那点事 |
| 15 | 是 | 简述CNN分类网络的演变脉络及各自的贡献与特点 |
| 16 | 是 | 为什么用F1-score |
| 17 | 是 | 了解全卷积网络FCN |
| 18 | 是 | 各种卷积方式串讲 |
| 19 | 是 | 特征融合concat和add的区别. |

### 机器学习

| 序号 | 是否完成 |       问题描述       |
| :--: | :------: | :------------------: |
|  1   |    否    |    SVM原理与应用     |
|  2   |    是    |    LR和SVM的比较     |
|  3   |    是    |    k-mens算法原理    |
|  4   |    是    | 三种主要集成学习思想 |
|  5   |    是    |     PCA算法原理      |

### python基础

汇总常考的

| 序号 | 是否完成 |                问题描述                 |
| :--: | :------: | :-------------------------------------: |
|  1   |    是    | python迭代器与装饰器 |
| 2 | 是 | python装饰器 |
| 3 | 是 | 引用赋值_浅拷贝与深拷贝 |
| 4 | 是 | python的C语言扩展 |
| 5 | 是 | python可变对象与不可变对象 |
| 6 | 是 | python包相对导入 |



## 数据结构

| 序号 | 是否完成 |        问题描述        |
| :--: | :------: | :--------------------: |
|  1   |    是    |        初识递归        |
|  2   |    是    |    递归返回值怎么定    |
|  3   |    否    |     排序算法大串讲     |
|  4   |    是    |  搜索问题之回溯大串讲  |
|  5   |    是    |   最优问题之动态规划   |
|  6   |    是    |    最优子结构与动规    |
|  7   |    是    | 记忆化递归初始值怎么定 |
|  8   |    是    |   最优问题之贪心算法   |
|  9   |    是    |    数组问题之前缀和    |
|  10  |    是    |   数组问题之差分数组   |
|  11  |    是    |   数组问题之滑动窗口   |
|  12  |    否    |   动态规划之子序列问题   |
|  13  |    否    |   最优问题之状态机   |
