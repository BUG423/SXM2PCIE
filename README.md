# 项目名称
开源V100 SXM2转PCIE底板
## 简介
* 本设计采用mini56012伏转5伏供电模组,在其他博主的验证方案中可以正常使用；
* 本设计采用显卡6+2P供电,参考其他博主的供电设计，能够满足 V100的电源功耗。
* 转接板配备了4PIN 风扇接口,以及电源指示灯,推荐使用水冷散热。
* 阻抗匹配设计中使用了85欧姆,并对差分信号线做了等长设计处理。PCB 中的M3定位筒柱有一些 DRC 检查错误，可以直接忽略，不影响直接使用。

## 注意
在下单生产时，请务必选择JLC3313板材。

## 实物展示（他人打样测试）
* 原版
![8b514249e1d1ea0bdb6959109ff6c79](https://github.com/user-attachments/assets/451c6a7c-6423-4efa-a64a-0d38cb5b3c5d)
* 正面
![39fb0bf8b6e774f39d12311e2be1036](https://github.com/user-attachments/assets/6584a89f-5d13-48cd-86e4-4cecf2932dab)
* 背面
![e8a629286c41ca29b921c7b4885e6b6](https://github.com/user-attachments/assets/0f1293d0-8996-45a7-a121-11de028abee3)
* 测试结果
![b92d47822ed4d3c1766a543c2e28b74](https://github.com/user-attachments/assets/e7a95bb1-5651-4015-a64c-021709370f55)

  
