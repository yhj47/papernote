# 《Squeeze-and-Excitation Networks》
## 一、abstract
针对标准卷积对所有通道特征同等加权、无法建模通道间依赖关系的问题，提出压缩 - 激励（SE）模块，通过全局信息压缩 + 通道注意力学习，自适应调整各通道权重，以极小的参数量代价提升模型精度。
## 二、网络架构
<img src="image/senet1.png" width="200" />

<img src="image/senet2.png" width="184" />


## 三、关键实验数据
<img src="image/senetresult.png" width="700" />