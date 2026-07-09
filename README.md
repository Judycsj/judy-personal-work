# judy-personal-work

个人主仓。

这个 repo 的目标不是保存所有历史材料，而是让你能长期沉淀：

- 个人规则
- 产品方法论
- AI 协作方式
- 行业知识
- 可复用模板
- 当前项目的工作过程

## 使用原则

这套仓库按“内容角色”拆层，不按主题堆在一起。

- `rules/`：会长期约束你和 AI 协作方式的规则
- `guides/`：任务说明、工作方法、starter、模板
- `knowledge/`：长期有效的知识沉淀
- `projects/`：正在进行或刚结束、还没提炼完的项目材料
- `references/`：链接、索引、系统入口、资料清单

一句话：

**项目先放 `projects/`，沉淀后再提炼进 `rules / guides / knowledge / references`。**

## 目录结构

```text
judy-personal-work/
├── README.md
├── rules/
├── guides/
├── knowledge/
│   ├── shopee-ads/
│   └── ai-native/
├── projects/
│   ├── active/
│   └── archive/
└── references/
```

## 每个目录放什么

### `rules/`
- 你的长期规则
- 和 AI 协作的默认边界
- 写作、分析、引用材料的统一标准

### `guides/`
- 一类任务怎么做
- AI-native workspace 怎么搭
- 当前可用的方法笔记
- 固定模板

### `knowledge/`
- 长期有效、不依赖当前公司的知识
- 行业认知
- 某个领域的结构化总结
- 适合保留多年、反复复用的内容

### `projects/active/`
- 当前正在写的文档
- 正在推进的项目
- 还没提炼好的阶段性内容

### `projects/archive/`
- 已结束项目的存档
- 存档前最好先把有价值的东西抽到别的层

### `references/`
- 链接索引
- 资料入口
- 系统/看板/数据源导航

## 推荐工作流

### 1. 新项目开始
- 在 `projects/active/<topic>/` 建目录
- 所有原始材料、草稿、阶段文档先放这里

### 2. 项目推进中
- 规则性的东西，抽到 `rules/`
- 任务说明、方法笔记、模板，抽到 `guides/`
- 长期有效知识，抽到 `knowledge/`

### 3. 项目结束后
- 把还需要保留的过程文档放到 `projects/archive/`
- 不再有复用价值的内容不必长期留存

## 当前已放入的内容

- `rules/pm-ai-collaboration-rules.md`
- `guides/ai-native-workspace-starter.md`
- `guides/method-notes.md`
- `guides/templates/`
- `knowledge/shopee-ads/sharing/shopee-ads-sharing-draft.md`

## 建议你优先补的内容

1. `references/knowledge-index.md`
2. `rules/pm-ai-collaboration-rules.md`
3. `guides/method-notes.md`

## 维护原则

- 不要把所有东西都放在根目录
- 不要把“项目过程”直接当“长期知识”
- 一份内容如果未来还会跨公司复用，优先提炼到 `rules / guides / knowledge / references`
- 方法论没长稳之前，不要过早拆成很多单独文件；先放在 `guides/method-notes.md`
