# 原始经营数据

各部门原始经营数据存放目录。建议 Excel 导出为 CSV 格式以便 AI 索引和分析。

## 目录

| 部门 | 目录 |
|------|------|
| 国际业务部 | intl-biz/ |
| 工程部 | engineering/ |
| 计划运营部 | planning-ops/ |

## 命名规范

### 单表数据

```
{部门}/
└── YYYY-MM/
    └── 数据说明.csv
```

### 多工作表 Excel（如国际业务部月报）

一表一 CSV，详见各部门 README：

```
intl-biz/YYYY-MM/
├── README.md
├── 汇总表.csv
├── 1组-陈子凡.csv
├── 明细表1-业务完成指标.csv
└── ...
```

国际业务部工作表对照见 [intl-biz/README.md](intl-biz/README.md)

## 使用说明

编写月报时，可将数据文件通过 `@data/` 引用，或直接粘贴表格数据。

## 字段口径

各数据字段的定义见 `docs/reference/核心经营指标口径.md`
