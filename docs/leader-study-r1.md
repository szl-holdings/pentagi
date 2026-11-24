# pentagi domain leader study r1 (propose-only)

Date: 2026-11-24. Method: web-verified leader landscape + governing-seat ratification (Kimi nonce T6-RULING-20261124-K1). Study pinned to pentagi HEAD 15f422553dda216d1e44c36041cd50c7bcdafeb8, fetched 2026-11-24. This card is documentation only; it changes no code, CI, config, or existing PR status. All absorb actions are FUTURE PROPOSALS (non-authorizing); implementation and merges remain separately reviewed and gated. Λ Conjecture 1: OPEN (advisory, never a closed theorem). No speedup, energy, or proven-trust claims; upstream performance claims are labeled as upstream claims only.

## Domain: autonomous AI penetration-testing multi-agent system, self-hosted (Go)

## Leaders studied (web-verified 2026-11-24)
1. Plan-and-Solve (https://arxiv.org/abs/2305.04091) - moat: prompting method that replaces zero-shot chain-of-thought with explicit plan formulation followed by step-by-step execution; the upstream paper claims improved reasoning over zero-shot CoT (upstream paper claim, not estate-verified).
2. PentestGPT (https://github.com/GreyDGL/PentestGPT) - moat: interactive pentest reasoning assistant with pentest-specific task decomposition and situated reasoning about target and privilege state.
3. PentAGI upstream (https://github.com/vxcontrol/pentagi) - moat: canonical fully autonomous multi-agent pentest stack in Go; per upstream README: sandboxed Docker isolation, 20+ bundled professional tools, self-hosted, multi-provider LLM support. Canonical upstream from which known forks derive (live-verified 2026-11-24).

## Absorb actions (FUTURE PROPOSALS, non-authorizing)
1. (Plan-and-Solve) Propose a design note describing plan-first task decomposition for agent delegation, limited to authorized testing workflows and without changing current agent behavior. Cost: one documentation-only design note and review cycle; limit: no implementation, no benchmark, and no claimed reasoning improvement beyond the labeled upstream paper claim.
2. (PentestGPT) Propose a future review of situated sub-agent design for target/privilege state tracking, comparing documented concepts with existing pentagi behavior before any design decision. Cost: one bounded review memo with code references; limit: no copied code, no new autonomy or capability claims, and no authorization for testing outside explicitly permitted scope.
3. (PentAGI upstream) Propose an honest fork-drift documentation pass comparing this estate copy against canonical upstream vxcontrol/pentagi at explicitly recorded revisions, identifying differences without prescribing backports. Cost: one append-only drift inventory and maintainer review; limit: never auto-merge or backport, never treat upstream README claims as estate-verified, and stop on duplicate or conflicting landed cards.
4. (Baseline) Propose preserving an append-only receipt for this study containing the governing nonce, pinned HEAD, corrected leader URLs verbatim, dedupe result, and PR reference. Cost: one documentation receipt update through the normal review path; limit: preserve authorized-testing-only language, head-sha pinning, and existing PR status, with no merge, implementation, integration, deployment, or excluded-lane change authorized.

## Do not do (per governing seat)

Do not merge, bypass the signature wall, or claim implementation beyond this card.
