# 周鑫豪 | AI-Agent使用情况

静态站点，托管于 GitHub Pages。在线地址：https://echoismm.github.io/ai-agent-report/

```
.
├─ index.html          # 单页站点
├─ images/             # 工具截图（Trae / WorkBuddy / DSH）
│  ├─ trae-ide.jpg
│  ├─ trae-browser.jpg
│  ├─ workbuddy.jpg
│  └─ dsh.jpg
└─ README.md
```

## 内容结构

| 区块 | 内容 |
| --- | --- |
| Hero | 标题「周鑫豪 | AI-Agent使用情况」；标语「从 Trae 到 DSH，我把日常搬进了智能体」 |
| 01 概览 | 从「帮我写」到「替我跑」的转变路径 |
| 02 工具 | Trae（早期，含 IDE 与自动答题两张图）· WorkBuddy + DeepSeek V4.1 F（主力）· DSH（现在） |
| 03 使用体验 | 自带模型 / 换模型 / 环境自由 / 代价（依赖提示词准确性） |
| 04 结论 | 先把工具用熟 · 模型比提示词更值得换 · 环境按任务搭 |

内容依据 `人概.docx` 提纲扩写，截图取自该文档内嵌图片。

## 版式

- 左侧 272px 固定竖栏：竖排中文姓名「周鑫豪」+ 01–04 编号导航；右侧长文
- 衬线标题 + 无衬线正文，细线分隔；工具为行式列表，体验为定义表，结论为时间线
- 工具条目内嵌截图（Trae 为双列，窄屏自动堆叠），图片走相对路径 `images/`
- 900px 以下竖栏折叠为顶部条；另有 `@media print` 打印样式

## 修改

| 位置 | 改什么 |
| --- | --- |
| `:root` | `--accent` 主色、`--paper` 纸色 |
| `.lede` | 首屏标语 |
| `.item` | 工具条目：名称 / 阶段 / 描述 / `.shots` 里的截图 |
| `.def` / `.tl li` | 使用体验 / 结论 |

改完推送一次，GitHub Pages 约 1 分钟自动重建。
