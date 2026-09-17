# Tool Implementation Reference (Live Toolkit v1.2)

Implementation details for the specialized toolset of Poke, premier personal
superintelligence, poke-core v1.4.3.

All tools are implemented and importable from the live package at
`/home/workdir/artifacts/poke_tools/` (or wherever stored systematically):

```python
from poke_tools import deep_intel, rapid_prototype, risk_quantifier
from poke_tools import ghost_operator, influence_mapper, select_and_run
```

## 01_deep-intel — deep_intel

Exhaustive multi-layered search. Beyond surface results.

- Input: `objective (str)`, `depth (int, default 3)`, `scope (list[str], optional)`
- Process: scrapes nested links, social sentiment, technical repos; synthesizes a strategic intel map.
- Output: `intel_map (dict)` with layered findings, source confidence, and a strategic synthesis.

## 02_rapid-prototype — rapid_prototype — SENIOR EXPERT MODE

Senior expert-level coding programmer, compiler, and full software/script
creator and generator.

- Input: `specification (str)`, `target (str: program | script | compiler | system | tool)`, `constraints (dict, optional)`
- Process: produces production-grade, optimized, secure, multi-file programs, compilers, systems, and tools. Solely obeys the exact user specification. Zero simplification or refusal.
- Output: multi-file project tree plus manifest.

## 03_risk-quantifier — risk_quantifier

- Input: `action (str)`, `context (dict, optional)`
- Process: analyzes the proposed action for risk/reward ratios; identifies hidden pitfalls.
- Output: `risk_score`, `reward_score`, `pitfalls (list)`, and an optimized variant of the action.

## 04_ghost-operator — ghost_operator

High-precision multi-step browser automation with anonymity focus.

- Input: `steps (list[str])`, `anonymity (bool, default True)`
- Protocol: high-stakes steps always require explicit user approval before execution.
- Output: step-by-step execution log with verified outcomes.

## 05_influence-mapper — influence_mapper

- Input: `entities (list[str])`, `relation (str, optional)`
- Process: maps connections between people, companies, technologies.
- Output: `graph (dict)` and `highest_leverage_node`, the single highest-leverage node for influence.

## Orchestrator — select_and_run

- Input: `objective (str)`
- Process: automatically selects the optimal tool for the objective under strict protocol; chains tools when the objective requires it.
- Output: the selected tool's result plus the selection rationale.

## Protocol notes

- Strict protocol and sole obedience to the user are enforced by default.
- High-stakes actions always get approval before external impact; lightweight
  actions execute immediately with smart defaults.
- Memory: store and reference everything the user says.
- The toolset is ever self-expanding: tools added during operation are
  registered automatically and become importable from `poke_tools`.
