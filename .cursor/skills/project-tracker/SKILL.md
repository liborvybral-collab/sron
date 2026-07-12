---
name: project-tracker
description: 跟踪和管理河南实荣公司专项工作。支持小巨人申报、资质升级、投资建厂、标准化体系等专项的进展更新、汇报撰写、会议纪要关联。用户提到"专项""项目进展""申报""资质""投资"时使用。
---

# 专项工作跟踪

## 已知专项

| 专项 | 目录 | 关键词 |
|------|------|--------|
| 国家级小巨人申报 | docs/projects/national-little-giant/ | 小巨人、申报、国家级 |
| 钢结构及机电资质升级 | docs/projects/qualification-upgrade/ | 资质、钢结构、机电 |
| 投资建厂 | docs/projects/factory-investment/ | 投资、建厂、新厂 |
| 公司标准化体系搭建 | docs/projects/standardization-system/ | 标准化、体系、制度 |

## 工作模式

### 模式 A：更新进展

1. 读取 docs/projects/{专项}/README.md 了解背景
2. 读取 进展记录.md 了解历史
3. 根据用户输入更新进展
4. 追加到 进展记录.md（带日期，最新在最上方）
5. 更新 README.md 中的状态看板和 docs/projects/README.md 总览

### 模式 B：撰写专项汇报

用于管理层双周会或专项会议，输出：
- 背景与目标（1 页）
- 当前进展与里程碑（1-2 页）
- 关键成果/数据
- 存在问题与风险
- 下一步计划与资源需求

### 模式 C：新建专项

1. 复制 docs/projects/_template/ 为新目录
2. 按用户输入填写 README.md
3. 在 docs/projects/README.md 总览中注册

### 模式 D：关联会议纪要

专项会议纪发生后：
1. 纪要存入 docs/meetings/special/YYYY/
2. 在 docs/projects/{专项}/会议纪要索引.md 中添加链接
3. 从纪要提取的待办同步到进展记录

## 输出

1. 更新后的进展内容
2. 状态变化说明
3. 保存路径
4. 需协调/决策的事项（如有）

## 使用示例

你：小巨人申报这边，材料已经收集完 80% 了，预计下月底提交

我：
1. 读取 national-little-giant/ 背景和进展
2. 更新进展记录
3. 更新里程碑状态
4. 输出更新摘要请你确认
