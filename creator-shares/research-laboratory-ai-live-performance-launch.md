# VIRTURA Research Laboratory：AI 实时演出研究立项公告

> 发布方：VIRTURA Research Laboratory
> 发布日期：2026年3月23日

---

## 发生了什么

VIRTURA Research Laboratory 正式在"感知接口"研究主线下列立 **AI 实时演出** 研究方向。

这不是新建一个项目，而是把之前散布在 SceneForge 文档里的 AI 模块研究、工具选型笔记和实验思路，正式收拢到一个有架构的层级里。

---

## 为什么这属于 Research Laboratory

Research Laboratory 的感知接口研究主线，一直在问这个问题：

> 如何设计让用户在感知层面经历状态转移的"进入机制"？

AI 实时演出是这个问题最具体的出口之一。它研究的是：如何在演出现场，让 AI 理解音频、理解视觉、理解身体状态，然后把这种理解转化为可感知的空间结构变化。

这是感知接口从理论走向实时实践的关键通道。

---

## 研究框架

### 三层混合架构

```
硬实时层（beat / onset / BPM）
    ↓
AI 语义层（段落 / 情绪 / 姿态）
    ↓
cue/state 决策层（状态切换 / 镜头调度）
    ↓
SceneForge viewer / 太空气球现场
```

### 5 个核心模块

| 模块 | 职责 |
|---|---|
| Input Adapters | 音频输入 / 系统 loopback / 摄像头 |
| Fast Analysis | onset / BPM / beat / RMS / band energy |
| AI Semantics | embedding / auto-tagging / face-pose-gesture |
| Cue/State Engine | 规则映射：信号 → 视觉状态 |
| Viewer/Web Preview | SceneForge 原本最擅长的部分 |

### 3 个优先实验

1. **音频 → state**：不做大模型，先用 aubio + madmom 建立 beat/section/energy → 视觉状态的最小可用映射
2. **摄像头 → cue**：用 MediaPipe Pose 检测表演者姿态，驱动 cue 触发
3. **离线曲库分析**：对 20 首常演曲目生成结构化 profile，演出时只做实时校正

---

## 与 SceneForge 和太空气球的关系

| 项目 | 角色 |
|---|---|
| **Research Laboratory** | 研究层：提出问题、建立框架、设计实验 |
| **SceneForge** | 实现层：把 AI 模块落地为产品功能 |
| **太空气球** | 应用层：在真实演出中验证和迭代 |

Research Laboratory 不做具体的产品开发，它提供研究基础，让 SceneForge 和太空气球可以在上面继续构建。

---

## 完整研究文档

- [AI 实时演出研究主入口](https://github.com/ewanqian/VIRTURA-SpacePort/blob/main/stations/research-laboratory/ai-live-performance/README.md)
- [技术选型报告](https://github.com/ewanqian/VIRTURA-SpacePort/blob/main/stations/research-laboratory/ai-live-performance/research/ai-modules-research.md)
- [实验方案](https://github.com/ewanqian/VIRTURA-SpacePort/blob/main/stations/research-laboratory/ai-live-performance/experiments/README.md)
- [SceneForge AI 路线图](https://github.com/ewanqian/SceneForge/blob/main/docs/ai-modules-roadmap.md)

---

**发布方：VIRTURA Research Laboratory**
**类型：实验室公告 / 研究立项**
