## 实验环境
```
Window10
RTX5060Ti
VS2019
CUDA 12.8
cuDNN 9.8
CMake 3.17
Git
Python 3.11
Paddle 3.2.1
```

### 官方提供的paddle_inference预测库，不支持RTX50系列，SM120架构

<img width="1076" height="542" alt="image" src="https://github.com/user-attachments/assets/2d6a4e1a-b64e-45e1-8c31-390e3d98b99b" />

### 基于RTX50显卡，源码编译的paddle_inference预测库，支持RTX50系列，SM120架构

<img width="1625" height="611" alt="image" src="https://github.com/user-attachments/assets/9e52d21d-0f6d-473a-8b6e-95f7e5ddb88a" />

具体编译教程，请查阅：[Win10 RTX50编译Paddle Inference C++预测库](https://mp.weixin.qq.com/s/c07vG550_KiNBwxoGDBMTA)
