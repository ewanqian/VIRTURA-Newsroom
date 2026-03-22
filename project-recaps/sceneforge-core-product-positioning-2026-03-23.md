# SceneForge：为什么它是核心产品仓

> 发布方：场景铸造
> 发布日期：2026年3月23日

---

## SceneForge 是什么

SceneForge 是当前唯一核心产品仓。

它的目标不是讲"生态中台"，而是一个明确、可验证、可发布的工具：

- 网页端场景查看器
- 舞台预演器
- cue / event-based 触发与编排
- 轻量网页发布与分享入口

一句话：SceneForge 用来把演出空间、装置场景和空间流程，做成可在网页中查看、预演和沟通的轻量工具。

---

## 为什么是核心产品仓

### 1. 它是唯一一个承载"产品逻辑"的仓库

VIRTURA-SpacePort 是公共前台和档案层，Newsroom 是发布出口，Research Laboratory 是研究层——它们都不承担"做出一个具体可用的工具"这件事。

SceneForge 承担。

### 2. 它有真实的第一个用例

SceneForge 已经有了一个非常具体的首个落地用例：**滴流演出场景查看器**。

这意味着 Digital Stage 不再只是理论推演，而是已经开始对应一个真实项目、一个真实工作流和一个真实沟通场景。

### 3. 它聚焦演出编排

SceneForge 当前只聚焦四件事：

1. 场景存档
2. 演出系统归档
3. 展览空间存档
4. 计划与路线图管理

不追求大平台，先做最小可用。这是最实际的路线。

---

## 与太空气球的阶段性重合

SceneForge 和太空气球在这个阶段有明显的重合点：

| 维度 | 太空气球 | SceneForge |
|---|---|---|
| 核心关注 | 真实演出实践 | 演出系统归档 |
| 当前阶段 | Alpha（2026-03）→ Beta（进行中） | 路线图规划 |
| AI 模块 | 应用层：实时音画 | 产品层：cue/state 引擎 |
| 关系 | 场景铸造的使用者 | 场景铸造的建设者 |

太空气球的 Alpha 阶段验证了 Arena + Spout + Unity 链路的可行性，Beta 阶段在积累练习时长和修正形象。SceneForge 正在规划 AI 模块如何接入这套链路，让它从手动操作升级为可编排、可复用、可分享的系统。

这不是替代关系，是层层叠加：太空气球验证底层，SceneForge 把验证结果固化成工具。

---

## AI 模块：三层混合架构

SceneForge 的 AI 模块定位很明确：**不是主控脑，而是分析层、识别层和辅助决策层**。

```
硬实时层（beat / onset / BPM）
    ↓
AI 语义层（段落 / 情绪 / 姿态）
    ↓
cue/state 决策层（状态切换 / 镜头调度）
    ↓
SceneForge viewer
```

完整 AI 路线图：[docs/ai-modules-roadmap.md](https://github.com/ewanqian/SceneForge/blob/main/docs/ai-modules-roadmap.md)

---

## 开发原则

- 先做最小可用，不做空平台
- 先验证工作流，不先扩概念层
- 所有新增能力都要能落到实际演出或空间沟通场景
- 保持仓库边界清晰，不相互污染

---

## 相关链接

- [SceneForge 主仓库](https://github.com/ewanqian/SceneForge)
- [AI 模块路线图](https://github.com/ewanqian/SceneForge/blob/main/docs/ai-modules-roadmap.md)
- [太空气球 Alpha/Beta 总结](https://github.com/ewanqian/VIRTURA-SpacePort/blob/main/stations/baloon-live-space/alpha-beta-summary.md)
- [AI 实时演出研究（Research Laboratory）](https://github.com/ewanqian/VIRTURA-SpacePort/blob/main/stations/research-laboratory/ai-live-performance/README.md)

---

**发布方：场景铸造**
**类型：产品定位说明**
