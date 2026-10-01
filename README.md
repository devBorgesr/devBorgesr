# devBorgesr

**Independent developer working on AI systems, retrieval evaluation, reproducible auditing, and experimental agent infrastructure.**

I build tools around a simple idea: AI systems should be inspectable enough that claims can be tested against evidence, not just demonstrated in a polished demo.

My current work is centered on retrieval/RAG evaluation, persistent memory for LLM systems, auditability, and agent tooling.

## Selected work

### [EDP v5](https://github.com/devBorgesr/edp_v5)

A persistent-memory runtime for LLM systems with hybrid retrieval, provenance, and explicit epistemic states such as contradiction, quarantine, and hypothesis.

The project is intentionally evidence-oriented: experiments, limitations, negative results, and reproducibility notes are documented alongside the implementation.

### [EDP Audits](https://github.com/devBorgesr/edp-audits)

Public registry for independent retrieval and RAG-quality audits.

Audits separate **measured results**, **observed patterns**, **hypotheses**, and **claims that are not supported by the available evidence**.

The registry also preserves audit scope, methodology, machine-readable outputs, and client/beta feedback when publication is authorized.

### [lab_edp](https://github.com/devBorgesr/lab_edp)

A reproducible retrieval-diagnostics project focused on explicit contracts, hashes, bounded claims, and technical evidence.

Its current scope is deliberately narrow: diagnose retrieved material without pretending to certify end-to-end answer quality.

### [Synapse-Forge](https://github.com/devBorgesr/Synapse-Forge)

Experimental workspace for reusable agent tooling and skill-oriented workflows.

## What I care about

- retrieval and ranking evaluation
- RAG diagnostics and auditability
- persistent memory for LLM systems
- provenance and epistemic state
- reproducible experiments
- agent tooling and human-in-the-loop systems
- documenting negative results instead of hiding them

## Current direction

I am turning EDP from an internal research system into a more disciplined evaluation ecosystem:

```text
retrieval / RAG system
        ↓
reproducible evidence
        ↓
independent audit
        ↓
query-level forensic analysis
        ↓
feedback / next experiment
```

The goal is not to produce impressive-looking scores. The goal is to make it easier to understand **what changed, where it failed, what is actually supported by the evidence, and what should be tested next**.

## Working principles

**Evidence before narrative.**  
If a result is inconvenient, it still belongs in the report.

**Scope before certainty.**  
A metric only means something when its population, reference, protocol, and limitations are explicit.

**Reproducibility before confidence.**  
Where practical, outputs are versioned, hashed, and tied to source snapshots.

**Hypotheses are not conclusions.**  
Observed co-occurrence is useful for designing the next experiment, not for inventing a causal story.

---

### Repositories to start with

- **Core system:** [edp_v5](https://github.com/devBorgesr/edp_v5)
- **Public audit registry:** [edp-audits](https://github.com/devBorgesr/edp-audits)
- **Retrieval diagnostics:** [lab_edp](https://github.com/devBorgesr/lab_edp)
- **Agent tooling experiments:** [Synapse-Forge](https://github.com/devBorgesr/Synapse-Forge)
