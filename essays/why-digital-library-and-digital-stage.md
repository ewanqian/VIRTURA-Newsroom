# Why Digital Library / Digital Stage Matters

- date: 2026-03-16
- status: public working article
- related repo: VIRTURA-Collective / VIRTURA-SpacePort / SceneForge
- related project: VIRTURA ecosystem upgrade
- author: Ewan Qian

## Core Point

很多演出、展览和研究内容的问题，不是创作时不存在，而是结束后很快失去结构，最后只剩零散素材和记忆。

`Digital Library / Digital Stage` 这条线要解决的，就是如何把一次性发生的内容，变成可以继续被观看、被整理、被再发布的系统。

## One Sentence Difference

- `Digital Library` 负责沉淀、编目、归档、索引和再调用
- `Digital Stage` 负责把已经沉淀下来的内容重新组织成可被观看、进入、沟通和传播的前台

一个解决“内容如何不散掉”，另一个解决“内容如何重新发生”。

## Digital Library

对 VIRTURA 来说，`Digital Library` 不是某一个单独仓库，而是一种跨仓组织原则。

它目前已经分布在几个不同宿主里:

- `VIRTURA-Collective`: 团队本体、作品入口、活动与协作入口
- `VIRTURA-SpacePort/knowledge-network`: 知识网络主宿主
- `VIRTURA-SpacePort/organization/works`: 旧作品档案源
- `VIRTURA-SpacePort/stations/space-salon`: 公共活动与沙龙档案
- `portfolio`: 个人项目、工作坊和个人研究视角下的文章归档

它处理的问题包括:

- 项目资料如何归档
- 作品版本如何追踪
- 协作者与公开资料如何索引
- 哪些内容可以公开，哪些应保留为内部源档

如果这一层没有建立，再好的项目也很容易在时间中失真。

## Why Space Salon Matters

`Space Salon` 很关键，因为它证明 VIRTURA 的档案层不只包括作品和理论，也包括活动、讨论、交流和方法传播。

截至目前，`Space Salon` 已经在 `VIRTURA-SpacePort/stations/space-salon/` 中形成了第一批正式档案:

- 系列入口
- 单次活动入口
- 对外发布版
- 内部完整记录版

这说明 `Digital Library` 已经开始容纳“发生过的公共事件”，而不是只容纳静态项目。

## Digital Stage

`Digital Stage` 关注的是再进入。

它处理的问题包括:

- 如何把归档后的内容重新组织成可观看的前台
- 如何从线下现场迁移到网页端、空间计算或其他公开入口
- 如何让作品在不同媒介中保持体验上的连续性

这也是为什么 `SceneForge`、`VIRTURA-SpacePort` 和 `VIRTURA-Collective` 需要同时存在，而不是被压成单一仓库。

它可以是一页网页、一个场景查看器、一段在线预览，也可以是一条演出版本的入口线。

## Why SceneForge Is The Current Stage Anchor

截至 `ace7c23`，`SceneForge` 的角色已经更具体了。

它现在不是“全场景大平台”，而是一个更真实的 WIP 工坊，当前集中做四件事:

- 场景查看
- 舞台预演
- cue / event-based 编排
- 网页分享与协作预览

这使它成为 VIRTURA 当前最现实的 `Digital Stage` 技术支点。

更重要的是，它已经有了一个非常具体的首个用例:

**滴流演出场景查看器**

这意味着 `Digital Stage` 不再只是理论推演，而已经开始对应一个真实项目、一个真实工作流和一个真实沟通场景。

## Why It Matters For VIRTURA

对 VIRTURA 来说，这条主线并不是抽象理论，而是正在发生的结构升级:

- `VIRTURA-Collective` 接住团队本体
- `VIRTURA-SpacePort` 继续担任知识网络和旧档案主宿主
- `VIRTURA-Newsroom` 承担发布出口
- `SceneForge` 承担数字舞台与工具实验

这四层一起工作，才能让作品、知识和工具真正形成生态，而不是彼此脱节。

## The Loop

对 VIRTURA 来说，比较理想的关系不是“先做资料仓，再做一个很酷的网站”，而是形成一个可以持续循环的闭环:

1. 项目、研究、活动、沙龙和演出先进入 `Digital Library`
2. 其中最值得被重新观看和传播的部分，进入 `Digital Stage`
3. `Digital Stage` 反过来又推动档案、元数据、索引和活动记录变得更清楚

换句话说:

- `Digital Library` 解决“如何积累”
- `Digital Stage` 解决“如何重新发生”

## Current Structure

截至 2026 年 3 月中旬，这套结构已经可以被这样理解:

- `portfolio`: 个人入口
- `VIRTURA-Collective`: 团队主入口
- `VIRTURA-SpacePort`: 公共导览前台、知识网络主宿主、旧档案源宿主、沙龙与站点档案宿主
- `VIRTURA-Newsroom`: 发布出口
- `SceneForge`: Digital Stage 相关的造景工坊与技术试验场

## Next Useful Steps

下一步最值当的，不是再发明更多名词，而是补齐现实结构:

- 给 `Space Salon` 建统一的活动元数据规范
- 给更多项目建立 `artifacts + manifest` 的档案结构
- 用 `SceneForge` 跑通“滴流演出场景查看器”的最小可用版本
- 继续把可公开引用的研究与复盘从内部文档迁到发布层
