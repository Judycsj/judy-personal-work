# AI Native Workspace Starter

## 1. 目标

这份 starter 的目标不是把团队一次性改造成 AI Native，而是用最小结构先把三件事跑起来：

- 让 AI 先知道去哪里找资料
- 让高频任务先有固定输出
- 让个人沉淀和团队沉淀分开

## 2. 最小目录结构

```text
workspace/
├── docs/
│   ├── common/
│   ├── team/
│   └── personal/<name>/
│       ├── README.md
│       ├── agent-rules/
│       ├── reports/
│       ├── notes/
│       ├── references/
│       └── workflows/
├── skills/
│   ├── common/
│   ├── team/
│   └── personal/
├── templates/
├── scripts/
└── projects/
```

这个结构最重要的不是目录名，而是两层分法：

- 第一层按 `common / team / personal` 分 scope
- 第二层按 `rules / reports / notes / references / workflows` 分用途

## 3. 六个核心模块

### 3.1 `docs/`

知识库入口。`common` 放跨团队共识，`team` 放团队资料，`personal` 放个人规则、草稿和沉淀。

### 3.2 `skills/`

可复用 workflow。优先沉淀高频任务，例如：

- 知识预检
- SQL / 指标路由
- RCA
- 收益汇总
- 周报 / review

### 3.3 `templates/`

固定输出骨架。最值得先放的通常是：

- PRD 模板
- RCA 模板
- rollout / 收益总结模板
- review / one-pager 模板

### 3.4 `scripts/`

放验证、同步、提交相关脚本。它解决的是“规则怎么稳定执行”，不是“文档怎么写”。

### 3.5 `projects/`

代码仓或业务工作台入口。让 AI、文档和代码在同一个 workspace 里协作。

### 3.6 `personal/<name>/`

个人层是整套结构里最重要的起点。个人先跑顺，再把成熟方法上升到 `team`。

## 4. 先建的 6 个文件

如果只想半天搭起来，先建这 6 个：

1. `docs/personal/<name>/README.md`
2. `docs/personal/<name>/agent-rules/knowledge-preflight.md`
3. `docs/personal/<name>/agent-rules/sql-metric-routing.md`
4. `docs/personal/<name>/agent-rules/report-writing.md`
5. `docs/personal/<name>/workflows/prd.md`
6. `docs/personal/<name>/references/knowledge-index.md`

## 5. 三条最值得先写的规则

### 5.1 知识预检规则

先定义遇到什么任务，AI 必须先查什么资料，再回答。

### 5.2 指标和 SQL 路由规则

先定义指标、口径、字段、收益分析默认去哪里查，避免凭记忆回答。

### 5.3 报告输出规则

先定义好报告长什么样。最值得统一的是：

- PRD
- RCA
- rollout / 收益总结
- review

## 6. 高频任务的最小模板

### 6.1 PRD

最少包含：

- 问题
- 目标
- 范围
- 规则
- 指标
- 风险
- 待确认问题

### 6.2 RCA

最少包含：

- 结论
- 非结论
- 证据
- 待验证项
- 后续动作

### 6.3 收益总结

最少包含：

- scope
- 核心 uplift
- 折算口径
- 是否可记账
- 风险 / tradeoff

## 7. 个人层和团队层怎么分

个人层负责：

- 个人工作习惯
- 个人资料入口
- 草稿和探索
- 个人常用 workflow

团队层负责：

- 共享知识
- 共享模板
- 共享 skill
- 统一输出标准

原则只有一条：

个人里先跑顺，稳定以后再升级到团队层，不要一开始就把个人偏好写进 shared 入口。

## 8. 从 0 到 1 的推进顺序

### 第一步：先选 2-3 个高频任务

优先选：

- PRD
- RCA
- rollout / 收益总结

### 第二步：先统一输出结构

不要先追求万能 prompt，先把“什么叫一份好的输出”定义清楚。

### 第三步：再建知识入口

先整理：

- 核心文档目录
- 指标和口径定义
- 历史方案和复盘
- 常用系统和数据入口

### 第四步：最后再沉淀成 skill / workflow

等团队已经知道“这类事情怎么做”，再把它固化成 skill。

## 9. 一句话原则

好的 AI Native workspace，不是文档多，而是结构清楚；不是 prompt 多，而是规则和模板清楚；不是一开始做很大，而是先把高频任务和个人层跑顺。
