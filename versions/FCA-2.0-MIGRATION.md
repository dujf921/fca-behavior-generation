# FCA 2.0 Migration Note

**Version:** FCA 2.0  
**Date:** 2026-05-21  
**Repository:** `dujf921/fca-behavior-generation`

---

## 1. Name Change

The model name is changed from:

**AFA Triplex Modulation Architecture (AFA-TMA)**

To:

**Functional Causal Architecture for Behavior Generation (FCA)**

Chinese:

**行为生成的功能因果架构**

Short Chinese reference:

**功能因果架构**

The prefix **AFA** is removed from the official model name.

The term **Triplex** is removed because the current model is no longer a three-part architecture.

The phrase **for Behavior Generation** is added because FCA is not a generic causal-architecture label. It specifically refers to a model of how human behavior is generated, stabilized, interrupted, or locked.

---

## 2. Structural Upgrade

### Previous 1.0 Structure

AFA-TMA 1.0 used the following core structure:

**DMN / FP / ECN + hormonal modulation axes**

This structure separated:

- DMN as template/narrative system
- FP as structured simulation system
- ECN as execution chain system

### Current 2.0 Structure

FCA 2.0 uses the following four-functional-system structure:

**SN → DMN → FP → ECN**

Chinese:

**入口敏感度 → 叙事模板 → 方案生成 → 执行承重**

---

## 3. Reason for the Upgrade

The upgrade is necessary for five reasons:

1. **Academic clarity**  
   DMN, SN, and CEN/ECN/FPN-related control systems already exist in large-scale brain-network research. FCA should not be presented as a competing anatomical network taxonomy.

2. **FP boundary correction**  
   FP is not claimed as an independent anatomical brain network. It is a functional solution-generation and structured-simulation layer.

3. **SN restoration**  
   The previous version lacked an explicit salience/sensitivity gate. FCA 2.0 restores SN as the entry-control system that determines which input enters foreground processing.

4. **Modulation correction**  
   Hormonal axes are retained only as secondary modulation biases. They are not independent networks and are not hard one-to-one mappings.

5. **Behavior-generation focus**  
   FCA 2.0 explicitly defines the model domain as behavior generation, including decision formation, relational dynamics, execution stability, and feedback-based behavioral reinforcement.

---

## 4. Four Functional Systems

| System | FCA Name | Primary Function |
|---|---|---|
| SN | Salience / Sensitivity Gate | Determines what enters foreground processing |
| DMN | Narrative / Context Template System | Supplies memory, narrative, identity, relational, and situational templates |
| FP | Forward Planning / Structured Simulation System | Generates plans, strategies, causal models, and alternative paths |
| ECN | Executive Chain / Execution Stability System | Converts generated plans into action sequences and maintains execution continuity |

---

## 5. Core Causal Loop

FCA 2.0 uses the following causal sequence:

```text
SN foregrounds input
↓
DMN supplies templates
↓
FP generates structure
↓
ECN executes sequence
↓
Reality returns feedback
↓
System updates or locks
```

Chinese:

```text
SN 推入前台
↓
DMN 提供模板
↓
FP 生成方案
↓
ECN 执行动作
↓
现实返回反馈
↓
系统更新或锁死
```

---

## 6. Hormonal Modulation Boundary

FCA 2.0 may still use hormonal axes as explanatory variables:

- Cortisol bias
- Dopamine bias
- Oxytocin bias

But the interpretation is changed.

Hormones are:

- modulation biases
- secondary explanatory variables
- system-state regulators

They are not:

- independent networks
- personality categories
- emotion labels
- hard one-to-one mappings

Important correction:

**Oxytocin is not defined as the main neurotransmitter of ECN execution.**

It is only treated as a safety/connection-related modulation factor that may indirectly support execution persistence.

---

## 7. Compatibility Statement

FCA 2.0 does not discard AFA-TMA 1.0 completely.

It preserves the useful 1.0 distinction between:

- narrative/template supply
- structured solution generation
- execution-chain stability

But FCA 2.0 adds the missing entry-control layer, corrects the anatomical/network-level ambiguity, and defines the architecture explicitly as a behavior-generation model.

The 1.0 model should be cited only as a historical version.

The current official model name is:

**Functional Causal Architecture for Behavior Generation (FCA)**

---

## 8. Recommended Citation

Functional Causal Architecture for Behavior Generation (FCA), Jeff, 2026.

Legacy version:

AFA Triplex Modulation Architecture (AFA-TMA), Jeff, 2025.
