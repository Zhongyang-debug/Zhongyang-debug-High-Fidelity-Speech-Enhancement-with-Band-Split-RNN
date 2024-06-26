# High-Fidelity-Speech-Enhancement-with-Band-Split-RNN

**轻量化模型设计**

2023 年 QQ 音乐与 AI lab 合作推出了一个子带分离模型 BSRNN，其基本原理包括两个方面，首先是对整个信号的一个频域进行子带的切分，切分之后从时域帧间序列建模，再对频域子带进行序列建模。

**相关领域应用情况**

音乐源分离：
[Music Source Separation with Band-Split RNN](https://arxiv.org/abs/2209.15174)

语音增强：
[High Fidelity Speech Enhancement with Band-Split RNN](https://arxiv.org/abs/2212.00406)

个性化语音增强：
[Personalized Speech Enhancement Combining Band-Split RNN and Speaker Attentive Module](https://export.arxiv.org/abs/2302.09953v1)

**数据集**

下载地址：https://datashare.ed.ac.uk/handle/10283/2791
    
**参考代码：**

https://github.com/sungwon23/BSRNN （调整 DPRNN 排列方式）

https://github.com/ruizhecao96/CMGAN （Metric GAN 学习客观评价指标）
