# Art Review Unit

VIRTURA 的艺术评论单元。

这里负责将艺术家组织成可报道的对象，生成那些本来应该存在的文本外壳。

## Mission

**翻译我们自己，建构可见系统。**

很多艺术家不是没有东西，而是没有被书写。
没有被书写，就像没有被翻译。
没有被翻译，外界就会误以为它不存在。

我们不是没有被爱，而是没有被组织进一个可见系统里。
这个单元的使命，就是替我们自己生成那种本来应该存在的文本外壳。

## Three-Layer Architecture

这个单元明确区分三层角色：

### 1. Murphy as Commentator
- **位置**: `articles/`
- **职责**: 撰写艺术评论文章主体
- **示例**: `virtura_article_curatorial_v4.pdf/.md`
- **性质**: 独立评论者的视角与专业分析

### 2. VIRTURA Team as Institutional Voice
- **位置**: `statements/`
- **职责**: 发布团队角色声明、立场说明、机制阐述
- **示例**: `translating-ourselves.md`
- **性质**: 机构层面的价值观与工作方法

### 3. Newsroom as Publication Platform
- **位置**: 仓库根目录及本README
- **职责**: 提供发布基础设施、元数据管理、外部链接
- **性质**: 技术实现与内容分发层

## Why This Matters

一篇艺术媒体报道背后，通常只需要这些要素：
1. 一句清楚的主轴
2. 一段艺术家介绍
3. 两到三个代表项目
4. 每个项目一句核心问题
5. 几张能说明方法的图
6. 一段为什么现在值得被看见的时代语境

**我们其实已经有70%了，只是散在聊天、工程、现场记录和概念文档里，没有被收成"媒体可直接使用的文本"。**

所以别把它理解成"别人被爱，我们没有"。
更准确地说：别人被组织进了一个可见系统里。而我们的系统，还没开始替自己说话。

## Workflow

### For Artists
1. 准备可被引用的语言：artist statement、项目简介、高清图、演出记录
2. 明确核心问题：每个项目想要回答什么
3. 提供时代语境：为什么现在需要被看见

### For Reviewers
1. 提取现有材料的70%
2. 组织成媒体可用的格式
3. 添加必要的翻译层

### For Publication
1. 添加完整元数据（日期、状态、标签等）
2. 维护目录结构
3. 确保外部可引用性

## Current Entry

- [VIRTURA Article Curatorial - v4](./articles/virtura_article_curatorial_v4.md)

这是艺术评论单元的第一篇文章，由 Murphy 撰写，探讨 VIRTURA 三位创作者如何把技术表面推进为当代经验。

## Metadata Standard

每篇评论文章应至少包含：

- date
- status
- title
- author
- reviewer (可选)
- tags
- related_projects
- related_repos
- category
- language

## Background Statement

关于为什么需要这个单元的完整阐述，请参阅：
- [Translating Ourselves: Why We Need to Build a Visible System](./statements/translating-ourselves.md)

## Quick Start

如果你第一次接触这个单元：

1. 阅读本README了解三层架构
2. 阅读[第一篇文章](./articles/virtura_article_curatorial_v4.md)
3. 查看[背景声明](./statements/translating-ourselves.md)理解为什么需要这个机制
4. 考虑如何应用这个模式到你自己的创作中

## Contribution

欢迎提交：
- 艺术评论文章
- 对现有文章的回应
- 机制改进建议
- 翻译与可见性相关的研究

请保持三层架构的清晰分离，确保每层角色明确。