# Behavior Generation Chain | Human Behavior FCA

Observable Output  
-> Foreground Entry  
-> Historical Template Matching  
-> New Structure Generation  
-> Execution Maintenance  
-> Feedback Update

## 1) Observable Output

- Input: action traces, pauses, repetition, interruption, state-change signals
- Process: register observable behavior as analysis entry
- Output: structured observation set for chain tracing
- Failure Mode: treating output as final cause and skipping chain localization

## 2) Foreground Entry

- Input: internal and external signals competing for processing priority
- Process: salience-based foreground selection and priority assignment
- Output: foreground input queue
- Failure Mode: threat or relationship signals saturate foreground and compress downstream capacity

## 3) Historical Template Matching

- Input: foreground queue plus stored templates
- Process: match and explain current input with historical structures
- Output: continuity-preserving explanation frame
- Failure Mode: old-template lock-in absorbs new feedback and blocks update

## 4) New Structure Generation

- Input: explanation frame, constraints, unresolved task demands
- Process: generate new causal paths and action structures beyond stored templates
- Output: executable new path candidates
- Failure Mode: analysis loops without producing new structure

## 5) Execution Maintenance

- Input: generated path candidates
- Process: maintain path under load as sustained action and reality-facing output
- Output: stable execution sequence
- Failure Mode: path exists but collapses under repetition load

## 6) Feedback Update

- Input: reality-facing outcomes from execution
- Process: update next-cycle competition, template weighting, and path choice
- Output: updated next-cycle generation conditions
- Failure Mode: feedback is absorbed by old templates and the loop reverts
