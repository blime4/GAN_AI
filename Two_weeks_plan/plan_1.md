# Plan_1

1. ### 安装TensorFlow

   ##### （应用于各类机器学习算法的编程实现），python3（主要编程语言）

   #####      jupyter notebook（一款开放源代码的 Web 应用程序，可让我们创建并共享代码和文档），anaconda（一个开源的Python发行版本

   [TensorFlow的安装](https://www.cnblogs.com/lvsling/p/8672404.html)

   (因为很早前已经安装了,所以这里你们自己想办法安装,安装cpu版本的先.)

2. ### 学习机器学习的一些基础知识

   ​            (可以跳过,直接看视频入手)

   > + ####  使用神经网络识别手写数字
   >
   >   1. **感知器**
   >
   >   ![1557994506047](/home/blime/.config/Typora/typora-user-images/1557994506047.png)
   >
   >   上面的这个东西就叫做感知器,
   >
   >   x1,x2,x3,这些是二进制输入,他们都有属于他们的==权重==,w1,w2,,,,,表示相应输入对于输出重要性的实数.
   >
   >   output是神经元的输出,结果为0或1.由分配权重后的总和$$\sum{j}\omega_jx_j$$小于或者大于一些==阈值(threshold)==决定
   >
   >   ![1557996868665](/home/blime/.config/Typora/typora-user-images/1557996868665.png)
   >
   >   感知器网络:
   >
   >   ![1557997234112](/home/blime/.config/Typora/typora-user-images/1557997234112.png)
   >
   >   上面有三层感知器,下一层的感知器都在权衡上一层的决策结果并做出决定,所以下一层的感知器可以比上一层中的做出更复杂和抽象的决策.以这种方式,一个多层的感知器网络可以从事复杂巧妙的决策
   >
   >   这里做两个变动
   >
   >   ​				:one:	把$$\sum{j}\omega_jx_j$$改写成==点乘==,$$\omega\cdot x \equiv  \sum{j}\omega_jx_j$$ 
   >
   >   ​				:two:	==偏置 b== $$b \equiv -threshold$$
   >
   >   则感知器的规则可以重写为:
   >
   >   ![1557997975881](/home/blime/.config/Typora/typora-user-images/1557997975881.png)
   >
   >   (从此以后都不会出现阈值threshold这个东西了)
   >
   >   2. **S型神经元**
   >
   >      
   >
   >   3. **神经网络的框架**
   >
   >   4. **一个简单的分类手写数字的网络**
   >
   >   5. **使用梯度下降算法**
   >
   >   6. **实现我们的网络来分类数字**
   >
   >   7. **迈向深度学习**
   >
   > + #### 反向传播算法如何工作
   >
   > + #### 改进神经网络的学习方法
   >
   > + #### 神经网络可以计算任何函数的可视化证明
   >
   > + #### 深度神经网络为何很难训练
   >
   > + #### 深度学习

   + #### 相关连接:

     > [书籍:	神经网络与深度学习](https://github.com/blime4/Mybook/blob/master/tensorflow/%E7%A5%9E%E7%BB%8F%E7%BD%91%E7%BB%9C%E5%92%8C%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0neural%20networks%20and%20deep-learning-%E4%B8%AD%E6%96%87_ALL.pdf)
     >
     > [视频:	bilibili莫烦教程](https://www.bilibili.com/video/av16001891?from=search&seid=5385868079792534716)
     >
     > [视频:	bilibili另一个教程](https://www.bilibili.com/video/av35974848?from=search&seid=10055890662041855685)

3. ### 通过学习卷积神经网络CNN来初步了解tensorflow

4. ### 创建一个github项目共享我们的工作内容以及存放一些书籍文档

 

