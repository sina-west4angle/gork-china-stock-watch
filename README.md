# China Tech Watch & USA Biotech Intelligence

宫崎骏风格投资情报小册子 · 只筛选「重要变化」

## 在线预览

直接打开根目录的 `index.html`（或 `china-tech-biotech-watch.html`）即可使用。

支持：
- 朗读功能（中文）
- 关注账号本地增删（localStorage）
- 按日期索引
- 所有重要变化均附带可点击的 X 原文链接

## 目录结构

```
.
├── index.html                      # 主网页（可直接浏览器打开）
├── china-tech-biotech-watch.html   # 同内容备份
├── data/
│   └── 2026-09-06.json             # 当日结构化数据备份
└── README.md
```

## 数据说明

- 所有每日内容以 JSON 形式保存在 `data/YYYY-MM-DD.json`
- 后续新增日期只需追加新的 JSON 文件
- 网页前端目前为静态嵌入内容，后续可改为动态读取 `data/` 目录

## 筛选标准

严格围绕以下三类核心问题与六类信息（A–F）：

1. 最近有哪些关于中国科技 / 美国生物公司的重要新信息？
2. 海内外投资者、券商、分析师、大V的观点（尤其看多/看空）？
3. 全球产业链、海外公司、政策与技术变化如何影响中国上市公司与美国生物医药？

A. 中国公司研究  
B. 券商/机构观点  
C. 大V/投资者观点变化  
D. 海外机构对中国公司关注变化（Attention / Sentiment / Fundamental 分开）  
E. 全球公司/产业链 → 中国公司映射  
F. 中国生物医药（新药、临床、FDA/NMPA、License、ADC、GLP-1 等）

最终只输出「重要变化」，并附带可验证的 X 来源链接。

## 时间

全部使用北京时间（UTC+8）。

## 关联项目

- 原始关注列表与情报系统：https://github.com/sina-west4angle/watchniuniuchanges

## 更新记录

- 2026-09-06：第一期内容上线（含 X 来源链接）
