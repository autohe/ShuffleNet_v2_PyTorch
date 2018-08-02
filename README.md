# ShuffleNet_v2_PyTorch

### 代码实现
1. 处理并加载自己的数据[ing]
2. 创建 ShuffleNetv2 网络结构[ing]
3. 网络参数初始化
4. 可视化网络结构
5. 设置超参数并训练网络
6. 加载预训练网络

### 背景知识
+ FLOPs 与速度的关系
+ 高效网络架构设计四项准则
+ ShuffleNetv1：逐点组卷积核(group pointwise convolution)，类瓶颈(bottleneck-like)，通道重排(channel shuﬄe)，ShuffleNet 单元
+ ShuffleNetv2 论文：通道分割(channel split)，ShuffleNetv2 单元

![Image text](https://raw.githubusercontent.com/Bugdragon/ShuffleNet_v2_PyTorch/master/ShuffleNetv2.png)
(a)ShuﬄeNet 基本单元；(b) 用于空间下采样 (2×) 的 ShuffleNet 单元；(c) ShuﬄeNet V2 的基本单元；(d) 用于空间下采样 (2×) 的 ShuffleNet V2 单元。DWConv：深度卷积 (depthwise convolution)。GConv：组卷积 (group convolution)。

### 版本条件
* Ubuntu 18.04LTS(64-bit)
* Python 3.6.5(pip3)
* torch 0.4.0(cpu)
* OpenCV 3.4.2
