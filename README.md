# RocketDebrisProject

# 面向多维动态遮蔽的虚实融合多模态数据集构建与算法研究

本项目旨在构建包含真实遮蔽场景的多模态数据集，并研究基于该数据集的火箭残骸检测算法。

## 🎯 项目目标

- 构建包含不同遮蔽程度（植被、地形、沙尘等）的火箭残骸多模态（图像+点云）数据集。
- 实现基于深度学习的目标检测算法，重点解决“动态遮蔽”和“多模态融合”难题。
- 提供完整的仿真-真实数据融合验证流程。

## 📁 目录结构
RocketDebrisProject/
├── data/ # 原始数据与预处理数据
├── configs/ # 模型与训练配置文件
├── models/ # 网络模型定义
├── datasets/ # 数据加载器与数据集类
├── tools/ # 工具脚本（预处理、可视化、评估）
├── deploy/ # 部署与推理代码
└── README.md # 项目说明文档
## 🚀 快速开始

### 1. 环境配置
bash
conda create -n rocket python=3.8
conda activate rocket
pip install torch torchvision opencv-python numpy pandas
### 2. 运行示例
（待填充：后续添加运行命令）

## 📊 数据集说明

- 数据采集：两个月后进行实地采集（模型：残骸模型，环境：山地、戈壁、林间）
- 仿真数据：使用 Unreal Engine 5 + AirSim 生成大规模合成数据
- 数据格式：图像（JPG/PNG）+ 点云（.bin/.pcd）+ 标注（JSON/XML）

## 📝 项目进度

- [x] 项目申报书撰写完成
- [ ] 开发环境搭建
- [ ] 公开数据集验证
- [ ] 仿真环境搭建
- [ ] 实地数据采集准备
- [ ] 模型训练与评估

## 👤 作者

- **姓名**：乔悦
- **邮箱**：[2148064660@qq.com]
- **单位**：[航天工程大学]

## 📚 参考文献

- KITTI 3D Object Detection Benchmark
- nuScenes: A multimodal dataset for autonomous driving
- ...（后续补充）
