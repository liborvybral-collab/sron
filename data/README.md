# 原始经营数据

各部门原始经营数据存放目录。建议 Excel 导出为 CSV/Markdown 格式以便 AI 索引和分析。

## 目录

| 部门 | 目录 |
|------|------|
| 国际业务部 | intl-biz/ |
| 工程部 | engineering/ |
| 计划运营部 | planning-ops/ |

## 命名规范

```
{部门}/
└── YYYY-MM/
    ├── README.md
    ├── *.xlsx          # 原件
    └── *.md            # markitdown 转换结果
```

## 使用说明

编写月报时，可将数据文件通过 `@data/` 引用。写月报优先引用 Markdown；核对公式与格式时回看 Excel 原件。
