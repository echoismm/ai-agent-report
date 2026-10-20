# Zhouxinhao · 个人主页

单文件站点：只有 `index.html`，零依赖、零图片、零 JS，双击即可预览。

## 版式

- 左右结构：左侧 272px 固定竖栏（竖排姓名 + 编号导航），右侧长文正文
- 衬线标题 + 无衬线正文的编辑式排版，章节用 `01–05` 编号与细线分隔
- 项目为**行式列表**（悬停左移 + 箭头淡入），不使用卡片
- 断点 900px 以下：竖栏折叠为顶部条，正文单列；另有 `@media print` 打印样式

## 发布

1. 新建仓库（任意名，如 `zhouxinhao-site`），上传 `index.html`；
2. `Settings → Pages` → Source 选 `Deploy from a branch`，`main` + `/ (root)`；
3. 访问 `https://<用户名>.github.io/zhouxinhao-site/`。

## 改内容

| 位置 | 改什么 |
| --- | --- |
| `:root` | `--accent` 主色、`--paper` 纸色、`--ink` 墨色 |
| `.rail` 顶部 | 姓名、`Vol. 01` 标签 |
| `.rail-nav` | 五个章节的编号与锚点 |
| `.lede` | 首屏那句主标语 |
| `.item` | 每条项目的标题、年份、描述、链接 |
| `.def` | 工具与技能（成对出现：名称 / 内容） |
| `.tl li` | 经历的年份与描述 |
