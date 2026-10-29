# xcc-embed-202401-2411020048
> 嵌入式系统课程作业仓库

## 个人信息
- 姓名：周炳权
- 班级：2024级 计算与智能学院
- 学号：2411020048

## 仓库说明
本仓库用于存放嵌入式系统课程全部实验代码，所有实验统一存放在此公开仓库，不新建多个独立仓库。
使用 GitHub Desktop 完成本地 commit + push，保留完整开发提交记录，不使用网页拖拽上传。

## 仓库目录
xcc-embed-202401-2411020048
├── README.md
├── .gitignore
├── lab01-led        # 实验1：LED流水灯
├── lab02-keyboard   # 实验2：4×4矩阵键盘（后续新增）

## .gitignore 功能说明
过滤Keil、STM32CubeMX编译临时文件、axf、hex以及庞大的HAL驱动库Drivers文件夹，只保留核心工程源码。

## 实验记录
### lab01-led
实验名称：STM32 LED流水灯
功能：实现LED循环流水点亮
开发平台：STM32F407 + STM32CubeMX + Keil5

> ⚠️ 备注：本工程省略Drivers HAL库，下载工程后使用STM32CubeMX重新生成代码即可编译运行。
