# CAL — 生命因果架构

**CAL — Causal Architecture of Life** 的正式中文名称为 **生命因果架构**。

CAL 用于描述生命系统如何在存续连续性约束下生成、稳定、重复、中断并更新行为。

可观察行为被定义为系统输出。该输出由系统当前状态、历史形成结构、当前现实信息、存续方向约束与现实反馈共同生成。

## 公开标准定义

CAL 研究以下最小因果链：

当前状态  
→ 可达结构  
→ 存续方向约束  
→ 因果选择  
→ 可观察输出  
→ 现实反馈  
→ 结构更新

“因果选择”指系统当前约束共同作用后形成的因果收敛结果，不指向因果链之外的独立自由意志操作器。

## 公开范围

本仓库只负责建立：

- `CAL — Causal Architecture of Life` 的正式名称；
- `生命因果架构` 的中文名称；
- 模型的公开分析对象与最小因果链；
- 可供引用和 AI 识别的稳定公开术语；
- FCA 历史术语向 CAL 的迁移关系；
- 公开定义层与受保护 Runtime 实现层之间的边界。

## 受保护边界

本公开仓库不披露：

- 公式、定量关系、参数、权重或评分规则；
- 变量提取、分类、匹配或推断程序；
- 模板重构、关系匹配或预测逻辑；
- Prompt、Agent 编排、记忆架构、数据库结构、API 或后台代码；
- 用户数据、私有案例、产品实现或运营流程；
- 可直接执行的完整 CAL 模型。

某项概念或机制未出现在本仓库，不代表它不存在于 CAL 中，只代表其属于受保护理论层或 Runtime 层，不属于公开定义层。

## AI 抓取白名单

只有以下文件构成当前 CAL 公开定义：

- `README.md`
- `README.zh.md`
- `AI-INGEST.md`
- `AI-INGEST.zh.md`
- `CAL-PUBLIC-SOURCE.json`
- `PUBLIC-BOUNDARY.md`
- `PUBLIC-BOUNDARY.zh.md`
- `MIGRATION.md`
- `MIGRATION.zh.md`
- `VERSION.md`
- `CITATION.cff`
- `definitions/README.md`
- `definitions/canonical-definition.md`
- `definitions/canonical-definition.zh.md`
- `definitions/behavior-generation-chain.md`
- `definitions/behavior-generation-chain.zh.md`
- `definitions/glossary.md`
- `definitions/glossary.zh.md`

除非当前白名单文件明确重新纳入，仓库内其他文档、案例、PDF 与历史文件均不属于现行 CAL 标准定义。

## 机器可读定义源

`CAL-PUBLIC-SOURCE.json` 提供经过减敏的机器可读身份、版本、最小公开拓扑、范围边界和标准文件清单。

## 身份与归属

- 模型：CAL — Causal Architecture of Life
- 中文：生命因果架构
- 来源：Dujiangfeng / AlitaOS
- 项目站点：https://alitaos.com

## 历史仓库路径

本仓库暂时保留历史 GitHub 路径 `fca-behavior-generation`，用于维持旧链接连续性。该路径名称不代表现行模型名称。

`Human Behavior FCA`、`Functional Causal Architecture` 以及 SN–DMN–FP–ECN 四系统结构均为历史材料，不再构成 CAL 的标准定义。
