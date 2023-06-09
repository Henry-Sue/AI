[TOC]



## 绪论

主要概念：

>  人工智能（AI）它是研究、开发用于模拟、延伸和扩展人的智能的理论、方法、技术及应用系统的一门新的技术科学.该领域的研究包括机器学习、计算机视觉、机器人、语言识别、图像识别、自然语言处理和专家系统等.

>  机器学习（ML）为人工智能的核心，专门研究计算机怎样模拟或实现人类的学习行为，以获取新的知识或技能，重新组织已有的知识结构使之不断改善自身的性能。

> 深度学习（DL）是机器学习领域的研究方向，是学习样本数据的内在规律和表示层次，这些学习过程中获得的信息对诸如文字、图像和声音等数据的解释让机器能够像人一样具有分析学习能力，能够识别文字、图像和声音等数据。

技术范围：

```mermaid
gragh

```

![image-20230327223419483](C:\Users\SHR\AppData\Roaming\Typora\typora-user-images\image-20230327223419483.png)

机器学习是当前比较有效的一种实现人工智能的方式；深度学习是机器学习算法中最热门的一个分支

> 相关领域概念：
>
> 自然语言处理（Natural Language Processing）：自然语言处理是指通过计算机技术来处理人类语言的一种方法，包括文本分析、语音识别、机器翻译等。
>
> 计算机视觉（Computer Vision）：机器视觉是指通过计算机技术来模拟人类视觉处理图像和视频的过程，包括图像识别、目标检测、视频分析等。
>
> 人工智能伦理（AI Ethics）：人工智能伦理是指在开发和使用人工智能技术时所需要遵循的道德和社会规范，包括隐私保护、安全性、公平性等方面。
>
> 人工智能应用（AI Applications）：人工智能应用是指在各个领域使用人工智能技术来解决实际问题的具体应用，包括无人驾驶、医疗诊断、金融风险管理等。
>
> 语音识别（Speech Recognition）：语音识别是指将语音信号转化为文本的一种技术，包括语音识别、语音合成等。
>
> 数据挖掘（Data Mining）：数据挖掘是指通过计算机技术来从大量数据中发现有用的信息和模式的一种方法。
>
> 推荐系统（Recommendation System）：推荐系统是指通过计算机技术来向用户推荐具有个性化和有效性的信息、产品或服务的一种方法，包括协同过滤、基于内容的推荐等。
>
> 智能代理（Intelligent Agent）：智能代理是指通过计算机技术来模拟人类的智能行为的一种方法，包括智能助手、智能机器人等。
>
> 人机交互（Human-Computer Interaction）：人机交互是指通过计算机技术来实现人类与计算机之间的有效沟通和交互的一种方法，包括自然语言交互、手势识别、虚拟现实等。
>
> 开放数据（Open Data）：开放数据是指公共数据资源对外开放，供公众使用和共享的一种数据形式，是人工智能等领域数据分析和挖掘的重要数据来源。
>
> 人机协同（Human-Machine Collaboration）：人机协同是指人类和计算机之间进行密切合作，通过相互交流和协同来实现各种任务的一种方法，包括共同决策、智能控制等。

## 机器学习

任务方向：

- 监督学习：通过设计奖励和惩罚机制，让计算机自主地学习最优策略。

- 无监督学习：指从大量无标记的数据中学习数据的内在结构和特征，常见的算法包括聚类、降维等。

- 强化学习：强化学习是指通过定义奖励和惩罚机制，让计算机自主地学习最优策略。

实现步骤：

1. 数据采集和预处理（特征选择和提取）
   - 模型假设 - 优化目标（评价函数） - 优化算法

2. 模型选择和训练（核心）

3. 模型评估和优化及应用

## 深度学习

其与机器学习框架一致，但比假设过程比机器学习更复杂，由于其已经超出数学式能表达的范畴，于是人们构建类似人的神经网络的结构进行模型建立

深度学习的核心是神经网络，它由多层神经元组成，在输入层接收原始数据，在输出层输出预测结果。神经网络的每一层又由多个神经元组成，每个神经元接收上一层神经元的输出，并通过激活函数将输出进行非线性变换。在训练时，通过反向传播算法来更新神经网络的参数，使得神经网络的输出与实际结果的误差最小化。

任务方向：

- 计算机视觉

- 深度卷积神经网络（CNN）

- 循环神经网络（RNN）
- 长短期记忆网络（LSTM）

实现步骤与机器学习相似，都是：假设 - 评价 - 优化

基本概念：

- 神经网络：多层神经元嵌套
- 神经元：每个能接受并输出的节点
- 深度：网络层数
- 激活函数：激活函数是神经元输出的非线性变换，常用的激活函数包括sigmoid、ReLU、tanh等
- 反向传播算法：反向传播算法是训练神经网络的核心算法，通过计算损失函数对神经网络参数的梯度来更新参数，使得神经网络的输出与实际结果的误差最小化。













