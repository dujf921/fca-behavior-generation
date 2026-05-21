# FCA Core Specification for Behavior Generation

**Model:** Functional Causal Architecture for Behavior Generation (FCA)  
**Chinese:** 行为生成的功能因果架构  
**Version:** 2.0  
**Status:** Core specification  

---

## 1. Purpose

FCA defines a functional causal architecture for behavior generation.

It is designed to model how a human behavioral output is produced, stabilized, interrupted, or locked through four functional systems:

```text
SN → DMN → FP → ECN
```

Chinese:

```text
入口敏感度 → 叙事模板 → 方案生成 → 执行承重
```

FCA is intended for:

- structured behavior analysis
- decision-process modeling
- relational-dynamics analysis
- execution-stability analysis
- AI runtime user-state modeling

FCA is not intended to replace clinical diagnosis, anatomical neuroscience, psychiatry, or medical treatment protocols.

---

## 2. System Layer Rule

FCA separates three levels that must not be mixed:

| Level | Meaning | FCA Handling |
|---|---|---|
| Anatomical level | Brain regions and biological structures | Not the claim of FCA |
| Network-concept level | Large-scale brain-network concepts such as DMN, SN, CEN/ECN/FPN | Used as reference background |
| Functional-causal level | Behavior-generation roles inside the model | FCA's primary level |

Core rule:

**FCA is a functional-causal model for behavior generation, not an anatomical brain-network taxonomy.**

Therefore:

- SN, DMN, and ECN are used as functional references based on established network concepts.
- FP is not claimed as an anatomical network.
- FP is defined as a functional solution-generation and structured-simulation layer.

---

## 3. Four Functional Systems

## 3.1 SN — Salience / Sensitivity Gate

SN determines whether an input enters foreground processing.

Input sources may include:

- bodily signals
- environmental changes
- social cues
- uncertainty
- threat-related signals
- task-relevant stimuli

SN output:

```text
foregrounded input
```

Chinese:

SN 决定输入是否进入前台处理。

输出不是方案，也不是叙事，而是：

```text
被推入前台的输入
```

---

## 3.2 DMN — Narrative / Context Template System

DMN supplies interpretive materials.

Its materials include:

- memory templates
- identity templates
- relational templates
- autobiographical material
- contextual simulations
- narrative framing

DMN output:

```text
template material
```

Boundary:

DMN does not generate structured solutions.

Chinese:

DMN 提供叙事、记忆、身份、关系和情境模板。

DMN 的输出是：

```text
模板材料
```

不是结构化方案。

---

## 3.3 FP — Forward Planning / Structured Simulation System

FP is the solution-generation layer.

FP integrates:

- SN foregrounded input
- DMN template material
- ECN execution feedback
- causal constraints
- future-state simulation

FP output:

```text
structured plan / strategy / causal path
```

Boundary:

FP is not an anatomical brain network claim.

FP is a functional layer used to separate solution generation from execution control.

Chinese:

FP 是方案生成层。

FP 的输出是：

```text
结构化方案 / 策略 / 因果路径
```

FP 的定义目的，是把“方案生成”从“执行控制”中拆出来。

---

## 3.4 ECN — Executive Chain / Execution Stability System

ECN converts FP-generated structures into action sequences.

ECN controls:

- action sequencing
- task maintenance
- interference suppression
- repeated-load bearing
- execution continuity
- behavioral feedback production

ECN output:

```text
executed action / missing action / broken action sequence
```

Boundary:

ECN does not generate new structural solutions.

Chinese:

ECN 把 FP 生成的方案转化为行动序列。

ECN 的输出是：

```text
已执行动作 / 缺失动作 / 断裂行动序列
```

ECN 不生成新方案。

---

## 4. Minimal Causal Equation

FCA can be expressed as:

```text
Behavior = ECN(FP(DMN(SN(Input)), Feedback))
```

Expanded:

```text
Input
→ SN foregrounding
→ DMN template supply
→ FP structural generation
→ ECN execution
→ feedback
→ system update or lock
```

Chinese:

```text
输入
→ SN 前台化
→ DMN 模板供给
→ FP 结构生成
→ ECN 执行
→ 反馈
→ 系统更新或锁死
```

---

## 5. Failure Modes

FCA defines four primary failure modes in behavior generation.

| Failure Point | Structural Failure | Observable Output |
|---|---|---|
| SN | wrong or excessive foregrounding | threat over-entry, distraction, uncertainty capture |
| DMN | template dominance or template rigidity | repeated narrative, identity lock, relational over-interpretation |
| FP | solution-generation collapse | no alternative path, circular analysis, decision freeze |
| ECN | execution-chain instability | action break, task abandonment, repeated non-completion |

Chinese:

| 断裂点 | 结构断裂 | 输出表现 |
|---|---|---|
| SN | 入口敏感度失衡 | 威胁过度进入、分心、不确定性捕获 |
| DMN | 模板占领或模板僵化 | 叙事重复、身份锁定、关系过度解释 |
| FP | 方案生成塌陷 | 无替代路径、循环分析、决策冻结 |
| ECN | 执行链不稳 | 行动断裂、任务放弃、反复未完成 |

---

## 6. Modulation Axes

FCA may use modulation axes to explain state shifts.

These axes are secondary.

They do not replace the four-system structure.

| Modulation Bias | Main FCA Effect | Boundary |
|---|---|---|
| Cortisol bias | increases threat-related foregrounding and DMN threat-template weighting | not an emotion label |
| Dopamine bias | supports FP search, simulation energy, and solution generation | not equivalent to pleasure |
| Oxytocin bias | may stabilize safety and relational continuity, indirectly supporting ECN persistence | not the main execution neurotransmitter |

Core rule:

**Hormonal axes modulate system state; they are not independent networks.**

---

## 7. Valid Inference Format

A valid FCA inference must follow this order:

```text
Observed behavioral output
→ failure point
→ system variable
→ causal sequence
→ predicted feedback pattern
```

Example:

```text
repeated non-completion
→ ECN execution-chain instability
→ low repeated-load bearing
→ action sequence fails before feedback is produced
→ DMN templates and FP confidence do not update
```

Chinese:

```text
可观察行为输出
→ 断裂点
→ 系统变量
→ 因果链
→ 反馈模式
```

---

## 8. Invalid Inference Format

The following are invalid FCA explanations:

- using personality as the cause
- using emotion labels as the cause
- treating FP as an anatomical network
- treating hormones as independent networks
- treating oxytocin as the main ECN execution transmitter
- claiming FCA is a clinical diagnostic system
- skipping SN when explaining input-entry behavior
- allowing DMN to generate structural solutions
- allowing ECN to generate new strategies

---

## 9. Minimal Citation

Functional Causal Architecture for Behavior Generation (FCA), Jeff, 2026.
