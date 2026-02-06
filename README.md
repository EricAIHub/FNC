# FNC: Foundations of Numerical Computing (数值计算基础)

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Python](https://img.shields.io/badge/python-3.8%2B-brightgreen.svg)
![Framework](https://img.shields.io/badge/framework-PyTorch%20%7C%20NumPy-orange.svg)
![CSDN](https://img.shields.io/badge/Column-CSDN-red.svg)

> 🌟 **用数值分析的上帝视角，重构深度学习与计算机视觉的底层逻辑。**
>
> 本项目是 CSDN 硬核专栏 **《FNC 数值分析》** 的官方同步代码仓库。我们拒绝枯燥的纯数学推导，致力于通过 **Human-AI 深度协作**，将经典的数值计算理论与现代深度学习实战（如 ResNet, Transformer 优化）彻底打通。

---

## 💡 为什么选择本项目？ | Why FNC?

- 🚀 **不只是公式**：每一个数学概念都配有 PyTorch/NumPy 实战代码，从实验中理解理论。
- 🧠 **跨学科视角**：深入探讨为什么神经网络会退化、梯度为什么爆炸，从数值稳定性找答案。
- 📂 **Obsidian 友好**：建议将本仓库直接作为 **Obsidian Vault** 打开，即可获得丝滑的知识图谱阅读体验。

---

## 📖 章节索引 | Table of Contents

### 🟢 第一阶段：数值计算基础 (Fundamentals)
*掌握计算机的“脾气”，理解误差的本质。*

- [【FNC数值分析 1.1】浮点数系统：从 0.1 + 0.2 ≠ 0.3 说起](<./FNC数值分析/Tutorials/Chapter-01/1.1 Floating-Point Numbers.md>)
- [【FNC数值分析 1.2】有效数字损失：详解“灾难性消去”与稳定性优化](<./FNC数值分析/Tutorials/Chapter-01/1.2 Loss of Significance.md>)
- [【FNC数值分析 1.3】前向误差与后向误差：为什么说“好算法”不怕输入错一点？](<./FNC数值分析/Tutorials/Chapter-01/1.3 Backward and Forward Error.md>)
- [【FNC数值分析 1.4】问题的条件性 (Conditioning)：为什么有的问题“天生”就难算？](./FNC数值计算基础/Tutorials/Chapter-01/1.4-Conditioning.md)
- [【FNC数值分析 1.5】数值稳定性：为什么简单的算法也会在关键时刻“翻车”？](./FNC数值计算基础/Tutorials/Chapter-01/1.5-Stability.md) *(Coming Soon)*

### 🟡 第二阶段：线性代数计算 (Linear Systems)
*解构所有 AI 算子的底层基石。*

- [【FNC数值分析 2.x】系列：LU分解、主元策略与病态系统处理](./FNC数值计算基础/Drafts/) *(实验室孵化中)*

---

## 🚀 快速开始 | Quick Start

1. **克隆仓库**:
   ```bash
   git clone https://github.com/EricAIHub/FNC.git
   ```
   
2. **环境配置**:
   ```bash
   pip install torch numpy matplotlib scipy
   ```
3. **使用建议**:
   本仓库文档采用 Markdown 编写，推荐使用 **Obsidian** 或 **VS Code** 获得最佳数学公式渲染效果。建议直接将本仓库作为 **Obsidian Vault** 打开，以享受双向链接与知识图谱带来的丝滑体验。

---

## ☕️ 支持与咨询 | Support & Consulting

如果您觉得本仓库的内容对您的科研或工作有启发，欢迎通过以下方式支持作者：

- **给予鼓励**：点击右上角 **Star** ⭐，这是对 0 粉丝起步博主最大的支持！
- **咖啡赞助**：支持硬核干货持续产出，扫描下方二维码请博主喝杯咖啡。

<div align="center">
    <img src="https://github.com/user-attachments/assets/ee439f78-cb5a-4234-9362-0cdae89438c1" width="220px">
    <p><b>扫码支持博主 (微信/支付宝)</b></p>
</div>

- **技术交流/报错纠错**：请提交 **Issue** 或在 CSDN 评论区留言。
 <!-- 
 **算法咨询/私教辅导**：WeChat: `Eric_Wangziyi` (备注：FNC咨询)。
 -->

---

## 📜 许可说明 | License
本项目采用 [MIT License](./LICENSE) 开源。

---
*Powered by EricAIHub | 关注数值分析，让 AI 更有底气。*
