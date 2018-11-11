# Digit_Recognizer
# 流程：
## 1. 数据预处理
### 1.1 载入数据
### 1.2 检测数据
### 1.3 标准化
### 1.4 Reshape
### 1.5 Label encoding
### 1.6 Split training and valdiation set(划分训练集和测试集)
## 2. 搭建模型
### 2.1 Set the CNN model,my CNN architechture is In -> [[Conv2D->relu]2 -> MaxPool2D -> Dropout]2 -> Flatten -> Dense -> Dropout -> Out
### 2.2 Set the optimizer and annealer(设置优化器等，使用 LR 衰减学习率)
## 3. Data augmentation 数据扩增 （使用数据扩增方法避免过拟合，常见的数据扩增方法有：灰度,水平翻转、垂直翻转,随机裁剪,反转,旋转,等等）
## 4. Evaluate the model
### 4.1 Plt training and validation curves
### 4.2 Confusion matrix (Confusion matrix can be very helpfull to see your model drawbacks)
### 4.3 可视化错误分类
