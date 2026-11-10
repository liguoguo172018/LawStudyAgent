# Changelog

本文件记录 LawStudyAgent 的主要变更。格式参考 [Keep a Changelog](https://keepachangelog.com/zh-CN/1.1.0/)，版本号遵循 [语义化版本](https://semver.org/lang/zh-CN/)。

## [Unreleased]

### 计划中

- 补充课程模块规范与更多示例（不包含受版权保护的内容）。
- 增加工作区一致性检查脚本（可选，零依赖）。
- 补充英文说明与宿主兼容性测试记录。

## [0.1.0] - 2026-11-10

首个公开版本，定位为早期实验版本。

### Added

- `SKILL.md`：Skill 入口，包含适用场景、启动与状态恢复流程、从资料到复习的完整工作流程、来源核验规则、文件与数据保护规则、输出规范与禁止事项。
- `references/knowledge-management.md`：资料接收与清单、课程配置、知识点原子化标准、条目 schema、关系类型、索引与进度、质量检查、备份规则。
- `references/learning-diagnosis.md`：记忆/理解/辨析/应用四层目标、诊断流程、题目设计、四项评分、六类错误归因、薄弱点登记门槛、掌握状态迁移表、复测规则。
- `references/source-management.md`：来源类型与证明任务、法条/案例/教材引用格式、核验流程、认知标签、冲突类型与处理步骤、版权边界。
- `references/review-system.md`：基于证据的复习触发、间隔参考、队列字段、按错误类型出题、薄弱点联动、中断恢复、周复盘。
- `templates/course-template.md`：课程配置模板（教材版本、大纲、章节、知识点、关联、来源、目标、评估）。
- `templates/learning-record.md`：学习记录模板（日期、主题、完成内容、作答证据、问题、下一步）。
- `templates/knowledge-gap.md`：知识薄弱点模板（知识点、表现、原因、掌握情况、验证证据、复测结果）。
- `examples/demo-course.md`：虚构课程《法理学导论》的完整走查示例，全部使用原创内容。
- `README.md`：项目介绍、设计理念、架构、目录、安装与使用、课程扩展、示例、限制、路线图、贡献与许可。
- `LICENSE`：Apache License 2.0。
- `.gitignore`：排除个人工作区、备份、环境文件与常见编辑器/系统文件。
- `.gitattributes`：统一文本文件为 LF 换行，避免跨平台换行差异。

### Changed

- 将原个人学习工作区中的**方法层**（学习流程、诊断规则、来源规则、复习策略）抽象为通用 Skill。
- 将民法学试点内容与通用内核分离：本版本不包含任何具体教材内容、教师课件或真实课程笔记。

### Security

- 未包含原工作区中的课件、教材、个人学习档案、会话记录与本地路径。
- 未包含任何凭证、密钥、Token 或个人信息。
- 示例课程为虚构内容，未引用受版权保护的教材原文。

### Known Limitations

- 未对任何 Agent 宿主做兼容性测试。
- 无自动化脚本、无后台提醒、无个性化遗忘模型。
- 诊断量表未经信度与效度检验。
- 仅有一个虚构示例课程，没有可直接使用的真实课程模块。

[Unreleased]: https://github.com/liguoguo172018/LawStudyAgent/compare/v0.1.0...HEAD
[0.1.0]: https://github.com/liguoguo172018/LawStudyAgent/releases/tag/v0.1.0
