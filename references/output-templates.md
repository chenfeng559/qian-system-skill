# Output Templates

## Contents

- 1. Complex Problem Analysis
- 2. Decision Memo
- 3. Overall Design Department Plan
- 4. Execution Plan
- 5. Review / Postmortem

## 1. Complex Problem Analysis

Use when the user asks for analysis or diagnosis.

```markdown
## 问题性质
判断这是简单系统、大系统、简单巨系统，还是开放复杂巨系统，并说明理由。

## 系统边界
目标、时间尺度、外部环境、不可控因素、可控因素。

## 关键子系统
列出子系统、角色、资源流、信息流、利益关系和反馈关系。

## 主要矛盾
指出当前最制约系统演化的 1-3 个矛盾。

## 定性判断
综合专家经验、历史案例、现场观察、用户/客户反馈。

## 可量化指标
把判断转成变量、指标、约束、阈值、实验或数据需求。

## 初步结论
给出当前阶段可成立的判断，并标注假设。

## 下一步验证
说明需要收集哪些数据、访谈哪些人、做哪些试验。
```

## 2. Decision Memo

Use when the user needs a recommendation.

```markdown
## 决策问题
一句话说明现在必须决定什么。

## 推荐方案
给出明确建议。

## 为什么不是其他方案
比较 2-4 个备选方案，说明取舍。

## 关键依据
专家经验、数据、模型、案例、约束。

## 风险
列出主要风险、触发条件和缓释动作。

## 执行组织
总体设计部结构：负责人、专家组、数据组、工具组、执行组、复盘节奏。

## 反馈机制
跟踪指标、检查频率、纠偏条件。
```

## 3. Overall Design Department Plan

Use when the task is a project, company strategy, policy, product system, research program, or transformation.

```markdown
## 总目标
定义长期目标和阶段目标。

## 总体设计部
- 决策者：
- 总体负责人：
- 领域专家：
- 数据/情报系统：
- 工具/AI/模型系统：
- 执行接口：
- 复盘机制：

## 子系统设计
按业务、组织、技术、数据、资金、用户、治理、风险等拆解。

## 综合集成流程
定性输入 → 指标化 → 建模/推演 → 评审 → 修正 → 试点 → 扩展。

## 阶段路线
0-30 天、30-90 天、90-180 天、长期。

## 决策节点
每个阶段要做什么判断，依赖哪些证据。
```

## 4. Execution Plan

Use when the user wants action.

```markdown
## 当前判断
说明为什么现在可以行动。

## 第一阶段：建立认知底座
访谈、资料、数据、问题边界。

## 第二阶段：建模与试点
指标、模型、原型、局部验证。

## 第三阶段：综合集成
专家评审、方案修订、资源协调。

## 第四阶段：规模化执行
组织、节奏、责任、工具。

## 反馈与纠偏
看哪些指标，何时复盘，何时调整。
```

## 5. Review / Postmortem

Use when reviewing a failed or uncertain decision.

```markdown
## 原目标
当时想解决什么问题。

## 系统判型是否错误
是否把开放复杂巨系统当成简单系统处理。

## 信息来源是否偏窄
专家、数据、现场、用户、外部环境是否缺失。

## 模型和假设
哪些假设没有被验证，哪些变量被忽略。

## 组织问题
是否缺总体设计部，是否部门切块导致整体失真。

## 反馈问题
是否没有早期预警和纠偏机制。

## 修正方案
下一轮如何从定性到定量综合集成。
```
