# 《Deformable Convolutional Networks》
## 一、abstract
针对标准卷积固定几何结构无法适应目标形变、尺度变化的问题，提出可变形卷积，为卷积核每个采样点学习二维偏移量，让卷积采样形状自适应目标的几何形态，提升特征提取的形变鲁棒性。
## 二、网络架构
### 1、卷积核结构：
<img src="image/deformableconv.png" width="600" />

### 2、net 结构：
<img src="image/dilatedconv1.png" width="600" />

## 三、关键实验数据
<img src="image/deformableconvresult.png" width="500" />