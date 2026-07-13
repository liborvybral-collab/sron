---
name: business-briefing
description: 编写河南实荣公司管理层双周会经营汇报 PPT 大纲。综合三个部门月报和专项进展，生成 PPT 页面结构及演讲备注。用户提到"经营汇报""PPT""管理层汇报"时使用。
---

# 编写经营汇报（PPT 大纲）

## 背景

- 汇报场合：管理层双周会
- 汇报形式：PPT（AI 输出大纲+备注，非 PPT 文件本身）
- 对应纪要：docs/meetings/management-biweekly/

## 你需要说明

- 目标期数（如"第12期"）和日期
- 侧重点（可选，如侧重某个专项或某个部门）
- 篇幅要求（默认 13-15 页）

## 我会自动做的

### 1. 收集输入

必须读取：
1. 三个部门当月月报
   - docs/reports/monthly/intl-biz/
   - docs/reports/monthly/engineering/
   - docs/reports/monthly/planning-ops/
2. 各专项最新进展（docs/projects/*/进展记录.md）
3. 上期经营汇报（docs/presentations/management-biweekly/）
4. 上期管理层双周会纪要（待办完成情况）
5. 模板：templates/presentations/管理层双周会经营汇报PPT大纲模板.md
6. 结构参考：references/汇报结构参考.md

### 2. 确定本期结构

| 页码 | 板块 | 内容来源 |
|------|------|----------|
| 1 | 封面 | 期数、日期 |
| 2 | 核心结论 | 3-5 条关键结论 |
| 3-4 | 经营指标概览 | 计划运营部月报 |
| 5-6 | 国际业务 | 国际业务部月报 |
| 7-8 | 工程项目 | 工程部月报 |
| 9-11 | 专项工作进展 | 各专项进展记录 |
| 12 | 问题与风险 | 三部门月报 + 纪要遗留 |
| 13 | 下阶段重点 | 综合 |
| 14 | 需决策事项 | 需管理层拍板的事项 |

### 3. 输出格式

每页按以下格式：

### 第 N 页：[标题]

**要点：**
- 要点 1
- 要点 2

**备注（演讲说明）：**
> 说明数据背景、补充细节

**数据来源：** docs/reports/monthly/...

### 4. 保存

docs/presentations/management-biweekly/YYYY/YYYY-MM-DD-第N期-经营汇报.md

### 5. 输出给你确认

先输出完整 PPT 大纲，你确认后再保存。

## 输出内容

1. 完整 PPT 大纲（含备注）
2. 数据缺失清单（如有）
3. 建议的图表类型（如"此页建议用柱状图对比三部门收入"）
4. 保存路径
