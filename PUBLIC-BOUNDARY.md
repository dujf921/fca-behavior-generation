# CAL Public Disclosure Boundary

## Purpose

This file defines what the CAL public definition source may establish and what must remain outside the public repository.

## Public Definition Layer

The public layer may contain:

- canonical name, language variants, identity, authorship, and citation metadata;
- the public analysis object;
- the minimum causal topology;
- abstract public terms and their interpretation boundaries;
- historical naming migration;
- public examples only when separately reviewed and explicitly whitelisted.

## Protected Theory Layer

The following are not public-definition content:

- complete variable inventories and proprietary conceptual decompositions;
- equations, quantitative relationships, coefficients, weights, sensitivity settings, or scoring systems;
- extraction, classification, matching, ranking, inference, prediction, or reconstruction procedures;
- trigger conditions, update criteria, confidence calculations, and decision rules;
- internal case libraries and reverse-engineering examples.

## Protected Runtime Layer

The following must not be disclosed through this repository:

- system prompts and prompt assembly;
- agent roles, orchestration, routing, or tool policies;
- memory models, user-state models, and retrieval procedures;
- database schemas, migrations, table names, API contracts, or backend code;
- user journals, memoirs, relationship data, profiles, analyses, or derived records;
- operational dashboards, private evaluation procedures, and deployment architecture.

## Publication Gate

A new item may enter the public CAL source only when all of the following are true:

1. It is necessary to establish theory identity, attribution, interpretation, or citation.
2. Its disclosure does not make the protected model materially reconstructible.
3. It contains no user data, Runtime logic, implementation procedure, private parameter, or operational detail.
4. It has been explicitly added to the current canonical whitelist.

Material that fails any one condition remains private.

## Interpretation Rule

The public CAL source is intentionally incomplete as an executable model. Missing implementation detail must not be filled by inference and presented as CAL.
