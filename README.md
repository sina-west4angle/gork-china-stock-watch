# China Tech Watch & USA Biotech Intelligence

宫崎骏风格投资情报小册子 · 只筛选「重要变化」

## 使用方式

1. **直接打开网页**  
   打开仓库中的 `index.html`（可用 GitHub Pages 或本地浏览器打开）。  
   页面会自动从 `data/2026-09-06.json` 加载当日内容。

2. **本地完整静态版**  
   对话中提供的 `china-tech-biotech-watch.html` 为内容完全内嵌的版本，无需网络即可使用。

## 功能

- 朗读（中文）
- 关注账号本地增删（localStorage）
- 所有重要变化附带可点击的 X 原文链接
- 数据与页面分离，后续只需更新 JSON

## 目录结构

```
.
├── index.html                 # 动态网页（从 data/*.json 读取）
├── data/
│   └── 2026-09-06.json        # 当日完整结构化数据
├── README.md
└── WEB_NOTE.md
```

## 数据更新流程

1. 新增或修改 `data/YYYY-MM-DD.json`
2. 如需新日期，在 `index.html` 中调整 `DATA_URL` 或做成日期选择器
3. 提交到本仓库即可

## 筛选标准

围绕三个核心问题 + A–F 六类信息，只输出「重要变化」，并附带来源链接。

## 关联项目

- https://github.com/sina-west4angle/watchniuniuchanges

## 更新记录

- 2026-09-06：第一期数据 + 动态网页上线
