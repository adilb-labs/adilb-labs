# Autonomous Agent Failure Diagnostic

## What this service is

A focused technical diagnostic for AI agents that **work sometimes, fail unpredictably, stall, waste actions/tokens, misuse tools, or improve in development but fail to transfer to real evaluation or production**.

The objective is not to replace your model by default. The objective is to determine **where useful capability is being lost** and identify the smallest defensible intervention with the highest expected operational value.

## Problems this diagnostic is designed for

This service is useful when an AI agent gets stuck in loops, performs well locally but degrades in production, fails inconsistently across repeated runs, overuses tokens/actions/tools, receives incomplete tool feedback, suffers runtime/scheduling/timeout effects, or improves after a change without the team being able to establish why.

## What you provide

Depending on the system, the diagnostic can work from a bounded set of materials such as agent source or relevant modules, prompts/policies, traces or trajectories, tool-call logs, benchmark/evaluation results, failure examples, runtime configuration, before/after outputs, and known constraints.

The minimum required evidence is agreed before analysis. Sensitive customer material is not published as part of the public case-study portfolio.

## Diagnostic framework

The investigation separates common failure layers instead of treating every bad outcome as a model problem:

1. **Perception / observation** — did the agent receive and interpret the relevant state correctly?
2. **Feedback fidelity** — did it receive a complete and current account of what its previous action changed?
3. **World-model integration** — did it integrate correct local evidence into the correct global model?
4. **Decision / commitment policy** — did it keep probing when it should have acted, or commit too early?
5. **Tool / runtime layer** — did timeouts, retries, queues, concurrency, or infrastructure distort behavior?
6. **Memory / context** — was relevant information unavailable, stale, duplicated, or overwhelmed?
7. **Evaluation / transfer** — is the apparent improvement real, or caused by selection effects, leakage, stochastic variance, or development/deployment mismatch?

## Deliverables

A standard diagnostic produces a **Failure Map**, **Evidence Ledger**, ranked **Root-Cause Candidates**, a **Minimal Experiment Plan**, a bounded **Repair Recommendation**, and an explicit **Claim Ceiling** stating what the evidence proves and what it does not.

## Optional implementation phase

After the diagnostic, a separate engagement can cover minimal repair implementation, regression tests, reproduction/qualification, before/after measurement, deployment-readiness evidence, and ongoing reliability monitoring.

The diagnostic does not automatically commit the client to implementation.

## What makes the approach different

**Diagnose before rebuilding.**

**Evidence over assertion.**

**Development improvement is not deployment transfer.**

**Artifact reproducibility is not the same as outcome reproducibility.**

**Preserve negative results so the team does not pay twice for the same failed idea.**

**Prefer one small causal delta over many simultaneous changes.**

## Public evidence

The methodology is informed by work performed during ARC-AGI-3 2026.

[ARC-AGI-3 2026 — Agent Diagnostics Case Study](../case-studies/arc-agi-3-agent-diagnostics.md)

Verified V8 public leaderboard score: **30.96**.

That score is used as evidence of a real working competition system, not as proof that any single diagnostic mechanism caused the result.

## Confidentiality boundary

Client work and private technical material are confidential by default. A public case study is created only from material that is already public or explicitly approved for disclosure.

No private Smart Factory implementation is required to be shared with the client or published.

## Best fit

This service is best suited to AI-agent startups, research teams, companies building tool-using LLM agents, benchmark/evaluation teams, workflow-automation systems, and engineering teams with expensive agent failures.

## Engagement path

**1. Diagnostic** — establish the failure surface and evidence.  
**2. Controlled verification** — test the highest-value hypotheses.  
**3. Minimal repair** — implement only the justified delta.  
**4. Qualification** — measure regression and realistic transfer.  
**5. Ongoing support** — optional periodic analysis for new failures or system changes.

## Start

[**Start a paid technical engagement**](https://github.com/adilb-labs/adilb-labs/issues/new?template=paid-engagement.yml)

The public intake issue is only for a high-level, non-confidential description. Do not post secrets, proprietary source, customer data, or trade secrets.
