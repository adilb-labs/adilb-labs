# Commercial Capability Map

This page translates proven or materially developed engineering capabilities into **client-facing services** without exposing private implementation details.

The governing rule is simple:

> **A capability is marketed only up to the strongest evidence that supports it.**

## Evidence states

- **SELL_NOW — STRONG PROOF**: materially demonstrated and suitable for paid client work now.
- **SELL_NOW — BOUNDED**: suitable for paid work within a clearly limited scope.
- **CONSULTING / DESIGN**: method and architecture are mature enough for advisory work, but a full production product is not claimed.
- **HOLD / R&D**: not marketed as an operational capability yet.

---

## 1. Software Assurance & Technical Audit

**Status: SELL_NOW — STRONG PROOF**

### Client problems
- AI-assisted / vibe-coded SaaS that works but is hard to trust
- architecture that has grown without clear production-readiness evidence
- unclear provenance between source, build, runtime, and observed result
- releases that cannot be reproduced reliably
- recovery work where code, requirements, retained evidence, and execution history disagree
- teams unsure whether to preserve, repair, replace, or rebuild

### Services
- SaaS / AI Technical Audit
- Production Readiness Review
- Software Assurance & Reproducibility Review
- Code / Architecture / Evidence Reconciliation
- Recovery Evidence Review
- Release Qualification Design
- Failure & Regression Analysis

### Typical outputs
- current-state evidence map
- source / build / runtime identity map
- blocker and risk classification
- Preserve / Repair / Replace decisions
- minimal remediation roadmap
- claim ceiling: what is proven, inferred, and still unknown

### Public claim ceiling
I do **not** equate compile success with product readiness, or static code with executed behavior.

---

## 2. AI Agent Reliability, Evaluation & Behavior Forensics

**Status: SELL_NOW — STRONG PUBLIC PROOF**

### Client problems
- agent stalls, loops, over-explores, or commits too early
- development gains do not transfer to production
- repeated runs produce materially different outcomes
- token/action/tool costs are high without proportional value
- team cannot isolate whether failure is model, memory, tools, runtime, scheduling, or policy

### Services
- AI Agent Reliability Audit
- Agent Generalization & Robustness Assessment
- Agent Behavior / Trajectory Forensics
- Action-Efficiency Optimization
- Agent Regression Test Design
- Failure Discovery / Red-Team Analysis
- Autonomy Readiness Assessment

### Public proof
ARC-AGI-3 2026:
- verified official V8 public leaderboard score: **30.96**
- submission ref: **57455070**
- exact-source rerun produced a different public score, creating direct evidence that artifact reproducibility and outcome reproducibility are not equivalent

[Read the ARC-AGI-3 case study](case-studies/arc-agi-3-agent-diagnostics.md)

---

## 3. Product Intelligence & Product Decomposition

**Status: SELL_NOW — BOUNDED / METHOD MATURE**

### Client problems
- idea is clear in the founder's head but not executable by a team
- AI coding started before requirements and product boundaries were closed
- MVP scope is expanding without a governing model
- requirements, risks, dependencies, architecture, and acceptance criteria are fragmented
- founder needs a build / repair / defer decision before spending more

### Services
- Product Genome Intelligence Report
- AI Product Decomposition Audit
- Product Scope & Risk Reconstruction
- MVP / V1 Boundary Review
- Requirement & Dependency Census
- Build-vs-Repair Decision Audit

### Typical outputs
- product definition
- user / role / flow decomposition
- domain model
- requirement census
- risk and failure map
- MVP / V1 boundary
- architecture direction
- acceptance criteria
- build / repair / defer recommendation

---

## 4. AI Project Recovery, Knowledge Handoff & Anti-Drift

**Status: SELL_NOW — BOUNDED / MATERIAL PROOF**

### Client problems
- project truth is scattered across chats, files, old branches, notes, receipts, and AI outputs
- a new AI model or developer cannot tell what is current vs historical
- handoff loses constraints, negative results, or next-step authority
- team repeatedly rebuilds work that already exists
- AI-generated changes drift away from the original product truth

### Services
- AI Project Handoff Package
- Legacy / AI-Assisted Project Recovery Audit
- Project Truth Reconstruction
- Cross-AI Knowledge Transfer Design
- Anti-Drift / Anti-Forgetting Architecture
- Evidence-Bound Handoff Review

### Typical outputs
- current-reality summary
- execution / decision timeline
- active vs historical vs superseded map
- preserved constraints and forbidden actions
- artifact / source identity registry
- structured handoff package
- next-safe-action boundary

### Proof boundary
A material external-AI transfer package and structured intake process exist. External AI output remains proposal-only until adjudicated; this is a safety property, not a limitation to hide.

---

## 5. Engineering Optimization, BOQ / Estimation QA & Workflow Automation

**Status: SELL_NOW — BOUNDED**

### Client problems
- estimating logic has edge cases that are not tested
- waste, fit/no-fit, quantity, or cost calculations are embedded in spreadsheets or fragile code
- BOQ / quantity takeoff workflows need QA, reconciliation, or automation design
- workshop / construction calculations need explicit rules and boundary tests
- client needs a reliable calculation contract before automating the whole workflow

### Services
- BOQ / Quantity Takeoff QA Review
- Estimation Workflow Audit
- Calculation Logic Validation
- Waste / Fit / Boundary-Case Analysis
- Engineering Spreadsheet-to-System Specification
- Estimation / Workshop Automation Design

### Evidence base
A real industrial optimization product program produced an exact numeric authority and boundary-proof discipline for fit, exact-fit, unusable remainder, usable remainder, kerf, stock, and waste-related logic.

### Claim ceiling
This does **not** claim that the full AluCut V1 product is commercially complete.

---

## 6. Document Automation & Evidence-Safe Output Design

**Status: SELL_NOW — BOUNDED / CONSULTING**

### Client problems
- PDF / invoice / quote / report templates contain business logic
- numbers differ between preview, PDF, print, and shared outputs
- internal prices/margins can leak into client-facing documents
- document generation lacks machine validation and reproducible schemas
- legal/commercial values are mutated by UI/template/AI layers

### Services
- Document Automation Architecture Review
- Quote / Invoice / Report Generation Workflow Design
- Render-Payload / Single-Source-of-Truth Review
- Document Schema & Fixture Design
- Internal-vs-Client Data Visibility Review
- Bilingual / Multi-output Document Workflow Design

### Evidence base
The industrial product program established a single-output-truth boundary, machine schema, conformance fixtures, validation-runner logic, and explicit visibility classes.

### Claim ceiling
A complete general-purpose document engine product is **not** claimed here.

---

## 7. Evidence & Document Forensic Intelligence

**Status: CONSULTING / DESIGN — NOT YET A FULL OPERATIONAL PRODUCT**

### Current safe offer
- forensic method / claim review
- evidence architecture design
- document provenance methodology review
- claim authorization and uncertainty design
- forensic product architecture / requirements audit

### Not claimed yet
I do not publicly claim a complete production forensic platform or universal automated fraud detector.

---

## 8. Product-Line / White-Label Architecture

**Status: CONSULTING / DESIGN**

### Client problems
- one codebase must support multiple brands or vertical editions
- product variants are diverging into forks
- shared core vs domain-specific logic is unclear
- requalification cost grows with each customer variant

### Services
- White-label Core Architecture Review
- Product-Family / Variant Decomposition
- Shared-Core vs Domain-Pack Boundary Design
- Rebranding / Multi-Edition Architecture Strategy

### Claim ceiling
This is offered as architecture and productization consulting; no claim is made that every proposed product-family implementation has already been commercialized.

---

## 9. Future licensable assets

**Status: HOLD until individually qualified**

Potential future forms include APIs, SDKs, libraries, components, templates, domain packs, rulesets, and reusable engines.

They are **not** automatically marketed merely because an internal implementation exists.

---

## Commercial operating rule

The public service portfolio intentionally favors:

1. **audits and diagnostics first** — fast, bounded, evidence-rich;
2. **repair / implementation second** — only after the real failure is known;
3. **qualification third** — prove the repair survived;
4. **retainer / repeat work fourth** — ongoing reliability, audits, and automation;
5. **licensing / productization later** — only for independently qualified reusable assets.

This reduces client risk and prevents unnecessary rebuilds.
