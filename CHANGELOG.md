# Changelog

## FCA 2.0 — 2026-05-21

### Renamed

- Official model name changed from **AFA Triplex Modulation Architecture (AFA-TMA)** to **Functional Causal Architecture (FCA)**.
- Chinese name changed to **功能因果架构**.
- **AFA** is no longer used as the official model prefix.
- **Triplex** is no longer used as the official structural descriptor.

### Structural Upgrade

FCA 2.0 upgrades the model from a three-part functional architecture:

```text
DMN / FP / ECN
```

To a four-functional-system architecture:

```text
SN → DMN → FP → ECN
```

Chinese:

```text
入口敏感度 → 叙事模板 → 方案生成 → 执行承重
```

### Added

- Explicit **SN** layer as the salience / sensitivity entry gate.
- Explicit boundary that **FP is not an anatomical brain network**.
- Explicit separation between:
  - input foregrounding
  - narrative/context template supply
  - structured solution generation
  - execution-chain stability
- Core specification file: `spec/FCA-CORE-SPEC.md`
- Terminology boundary file: `spec/FCA-TERMINOLOGY.md`
- Migration note: `versions/FCA-2.0-MIGRATION.md`

### Corrected

- Hormonal axes are now defined as **secondary modulation biases**, not independent networks.
- Cortisol / dopamine / oxytocin are not treated as hard one-to-one mappings.
- Oxytocin is not defined as the main neurotransmitter of ECN execution.
- ECN is restricted to execution sequencing and execution stability.
- DMN is restricted to narrative, memory, identity, relational, and contextual template supply.
- FP is restricted to forward planning, structured simulation, and solution generation.

### Compatibility

AFA-TMA 1.0 remains a historical version reference only.

The current official model is:

```text
Functional Causal Architecture (FCA)
```

---

## AFA-TMA 1.0 — Historical

Original public version.

Core structure:

```text
DMN / FP / ECN + hormonal modulation axes
```

Known limitations corrected in FCA 2.0:

- SN was not explicitly represented.
- Triplex naming no longer matched the expanded model.
- FP could be misread as an anatomical network.
- Hormonal modulation axes could be misread as hard one-to-one mappings.
