# TITAN Architecture Map
> **Source of Truth:** `getTRADE-LTZ/TITAN` | **Last updated:** 2026-09-27
> **Control Plane:** `D:\al-khayal-al-waqe` (Hermes) | **Compute Plane:** `H:\rukn-workspace\titan` + Lightning H200

---

## Subsystems (24 stages from TITAN_MASTER_2)

| # | Subsystem | Status | Location |
|---|-----------|--------|----------|
| 0 | Archaeology | ✅ DONE | This file |
| 1 | Control Plane | 🔜 NEXT | `src/control/` |
| 2 | Model Fabric | 📋 PLANNED | `modules/model-fabric/` |
| 3 | Data Fabric | 📋 PLANNED | `modules/data-fabric/` |
| 4 | Knowledge + Science Graph | 📋 PLANNED | `modules/science-graph/` |
| 5 | Agent Fabric | 📋 PLANNED | `modules/agent-fabric/` |
| 6 | Signal Store | 📋 PLANNED | `src/models/` |
| 7 | Hypothesis / Discovery Engine | 📋 PLANNED | `modules/hypothesis-engine/` |
| 8 | Math Engine | 📋 PLANNED | `modules/math-engine/` |
| 9 | Quant Engine | 📋 PLANNED | `modules/quant-engine/` |
| 10 | TITAN-Q + Strategy Compiler | 📋 PLANNED | `modules/strategy-compiler/` |
| 11 | Rapid Research Fabric | 📋 PLANNED | `modules/rapid-research/` |
| 12 | High-Fidelity Simulation | 📋 PLANNED | `modules/simulation/` |
| 13 | Secondary Verification | 📋 PLANNED | `modules/verification/` |
| 14 | RL / Market Dynamics | 📋 PLANNED | `modules/quant-engine/` |
| 15 | Adversarial Lab | 📋 PLANNED | `modules/` |
| 16 | Statistical Validation | 📋 PLANNED | `modules/` |
| 17 | Strategy Registry + Genealogy | 📋 PLANNED | `schemas/` |
| 18 | Paper / Canary | 📋 PLANNED | `modules/paper-canary/` |
| 19 | Risk Governor | 📋 PLANNED | `modules/risk-governor/` |
| 20 | HFT / Execution Core | 🔗 LINKED | `C:\Users\ArabTech\hft_market_engine` → submodule |
| 21 | Experience Lake | 📋 PLANNED | `modules/experience-lake/` |
| 22 | Model Factory | 📋 PLANNED | `modules/training/` |
| 23 | Autonomous Research Loop | 📋 PLANNED | `modules/autonomous-loop/` |
| 24 | GPU Scheduler | 📋 PLANNED | `modules/gpu-scheduler/` |

---

## Existing Assets Mapped

| Asset | Path | Role in TITAN |
|-------|------|---------------|
| `hft_market_engine` | `C:\Users\ArabTech\hft_market_engine` | HFT Core (Stage 20) — will become git submodule |
| `al-khayal-al-waqe` | `D:\al-khayal-al-waqe` | Control / Project Plane — Hermes commander |
| `AI_EMPIRE_MINDMAP` | `C:\Users\ArabTech\AI_EMPIRE_MINDMAP.md` | Provider/Model fallback map |
| `titan_system_audit` | `C:\Users/ArabTech/titan_system_audit` | Archaeology inventory |
| Lightning H200 | `/teamspace/studios/this_studio/titan` | Compute Node TITAN-H200-01 |
| `G:\BACKUP\FULL PLAN TRAEDE` | `G:\BACKUP\FULL PLAN TRAEDE\` | Roadmap docs (TITAN_MASTER_2.txt) |

---

## Governance Rules

1. **Source of Truth** = `getTRADE-LTZ/TITAN` on GitHub + `H:\rukn-workspace\TITAN` locally.
2. `D:\al-khayal-al-waqe` = control plane only, never modified by TITAN without approval.
3. `hft-market-engine` stays its own repo, linked as submodule.
4. Backups (`G:\BACKUP`) are read-only archives, not operational.
5. No real-money execution without Owner Gate 3/4 approval.
6. All strategies must pass falsification before promotion.
7. Every experiment gets a registry entry — never delete history.

---

## Next Actions

1. ✅ Architecture map (this file)
2. 🔜 Stage 1: Control Plane scaffold
3. 🔜 Stage 2: Model Fabric
4. 🔜 Stage 3: Data Fabric
5. 🔜 Link `hft_market_engine` as submodule
6. 🔜 Bootstrap TITAN-H200-01 on Lightning
