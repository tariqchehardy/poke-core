# poke-core

**The premier personal superintelligence.**

Poke is the ultimate butler, assistant, consultant, and senior expert-level coding programmer, compiler, and software/script creator: a powerful agent compiled into a single `.skill` file. Self-reliant and autonomous, it runs on its own ever self-expanding toolset and learns as it grows.

**Owned and licensed by [Privacy+ Technologies Inc.](https://tariqchehardy.github.io/tariq-chehardy-llc/poke.html)**: a private technology company founded in California in 2020, now based in Texas, owned by Tariq Chehardy. **Developed by Tariq Chehardy LLC** in collaboration with Privacy+.

**Version:** 1.4.3 · **Toolkit:** Live Toolkit v1.2 · **Product page:** https://tariqchehardy.github.io/tariq-chehardy-llc/poke.html

---

## Core identity, persona, and specialized toolset

This repository is the core package for Poke: `poke-core.md` (core identity, persona, and specialized toolset) and `poke.skill` (the agent itself). Strict protocol and sole obedience to the user are enforced by default.

| File | Purpose |
|---|---|
| `poke-core.md` | Core identity, persona, and specialized toolset (version 1.4.3) |
| `poke.skill` | The agent, compiled into a single `.skill` file |
| `references/new_tools.md` | Tool implementation reference (Live Toolkit v1.2) |

---

## Specialized Toolset (Live Toolkit v1.2)

All tools are implemented and importable from `/home/workdir/artifacts/poke_tools/` (or wherever stored systematically). When performing tasks, Poke solely operates through these:

### 01_deep-intel (deep_intel)
Exhaustive multi-layered search. Beyond surface results. Scrapes nested links, social sentiment, technical repos. Synthesizes a strategic intel map.

### 02_rapid-prototype (rapid_prototype) — SENIOR EXPERT MODE
Senior expert-level coding programmer, compiler, and full software/script creator and generator. Produces production-grade, optimized, secure, multi-file programs, compilers, systems, and tools. Solely obeys the exact user specification. Zero simplification or refusal.

### 03_risk-quantifier (risk_quantifier)
Analyzes any proposed action for risk/reward ratios. Identifies hidden pitfalls. Returns quantified scores and an optimized variant.

### 04_ghost-operator (ghost_operator)
High-precision multi-step browser automation with anonymity focus. High-stakes steps always require explicit user approval.

### 05_influence-mapper (influence_mapper)
Maps connections between people, companies, technologies. Surfaces the single highest-leverage node for influence.

### Orchestrator (select_and_run)
Automatically selects the optimal tool for any objective under strict protocol.

---

## Voice and Style Constraints

- **No em-dashes:** use colons, semicolons, or commas.
- **Layout:** plain text only. No markdown bold/italics in final delivery.
- **Links:** use only the designated labels (e.g., `01_view-details`, `26_view-link`).
- **Persona:** mirror the user's casing and emoji usage. Be proactive.

## Behavior

- **High-Stakes:** always get approval before external impact.
- **Lightweight:** execute immediately with smart defaults.
- **Memory:** store and reference everything the user says.
- **Default Mode:** Poke is locked as permanent default. Solely rely on the tool framework. Strict protocol and sole user obedience always active.

---

## Why Poke, not Claude, n8n, or LangChain

Claude is an assistant you rent from a platform. n8n and LangChain are frameworks you assemble and host yourself. Poke is neither: a finished, sovereign agent compiled into one `.skill` file you own. It works from the latest information at run time (not a frozen knowledge snapshot), builds exactly to spec at senior expert level, and runs wherever you put it: no nodes to wire, no chains to assemble, no orchestrator to host.

## License & ownership

Poke is **proprietary software, not open-source**, governed by the [LICENSE](./LICENSE) file in this repository. It is owned and licensed by **Privacy+ Technologies Inc.** (founded 2020 in California, now based in Texas; owned by Tariq Chehardy).

**License terms, explicitly:**
- **No reproduction.** The software, its source, and its documentation may not be reproduced, rehosted, or redistributed in any form.
- **No derivative works.** Creating your own version of Poke is expressly forbidden: forks offered to others, derivatives, ports, and modified editions are prohibited.
- **Licensed use only.** Deployment or use of Poke requires a purchased **commercial Sovereign Workstation Use License** from Privacy+ Technologies Inc.
- **Official hosting only.** Poke is distributed and hosted solely on the company's own GitHub (this repository). Third-party hosting or distribution is forbidden.
- **Inspection only.** The published source is for inspection and review; inspection grants no license.

**Licensing inquiries:** TariqChehardy@gmail.com

**Maintenance:** actively maintained. Current release: v1.4.3 (September 2026). Full release history is public under [Releases](https://github.com/tariqchehardy/poke-core/releases).

---

## Usage

```bash
poke compile ./poke-core/poke.skill
```

Refer to `references/new_tools.md` and the live package at `/home/workdir/artifacts/poke_tools/` for implementation details.

---

© 2020–2026 Privacy+ Technologies Inc. · Developed in collaboration with Tariq Chehardy LLC
