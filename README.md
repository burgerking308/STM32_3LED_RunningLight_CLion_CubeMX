# STM32_3LED_RunningLight_CLion_CubeMX
# 电控组第二次培训作业
- **姓名**：郝博文
- ***_**20263001713**_***

## 项目概述
本项目使用 STM32CubeMX 完成GPIO引脚配置，设置User Label将三个LED引脚命名为LED0、LED1、LED2；使用CLion打开工程进行代码开发，实现三LED流水灯，切换间隔500ms。
项目包含基础阻塞延时版本

## 实现思路
**基础版本（HAL_Delay阻塞延时）**
在while循环中，每次只点亮一个LED，其余熄灭，调用`HAL_Delay(500)`等待500ms后切换下一个LED。
