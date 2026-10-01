# devBorgesr

**Independent developer working on AI systems, retrieval evaluation, reproducible auditing, and evidence-driven RAG diagnostics.**

I build tools around a simple principle: claims about AI systems should be testable against explicit evidence, not just demonstrated in a polished demo.

## For audit clients

The client-facing work lives in **[EDP Audits](https://github.com/devBorgesr/edp-audits)**.

That repository is the public delivery and review layer for retrieval/RAG audits. It separates measured results, observed patterns, hypotheses, and claims the available evidence does not support. Private client data, credentials, proprietary corpora, and raw non-public exports do not belong in the public registry.

The research repositories below are **not** the storage or delivery backend for client audit data.

## Selected work

### [EDP Audits](https://github.com/devBorgesr/edp-audits)

Public registry for independent retrieval and RAG-quality audits, with explicit scope, methodology, reproducibility artifacts, limitations, and beta/client feedback when publication is authorized.

### [EDP v5](https://github.com/devBorgesr/edp_v5)

Research runtime for persistent LLM memory, hybrid retrieval, provenance, and explicit epistemic states such as contradiction, quarantine, and hypothesis.

It is a research system and evidence source — **not a requirement for the audit service and not a client-data repository**.

### [lab_edp](https://github.com/devBorgesr/lab_edp)

Research and diagnostic laboratory for retrieval instrumentation, reproducible experiments, sanitization, and bounded technical claims.

Public client deliverables belong in `edp-audits`, not in this laboratory repository.

## Current direction

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

The goal is not to produce impressive-looking scores. The goal is to make it easier to understand **what changed, where it failed, what the evidence actually supports, and what should be tested next**.

## Working principles

**Evidence before narrative.**  
Inconvenient results still belong in the report.

**Scope before certainty.**  
A metric only means something when its population, reference, protocol, and limitations are explicit.

**Reproducibility before confidence.**  
Where practical, outputs are versioned, hashed, and tied to source snapshots.

**Hypotheses are not conclusions.**  
Observed co-occurrence can justify the next experiment; it does not establish causation.

---

### Repositories to start with

- **Client-facing audit registry:** [edp-audits](https://github.com/devBorgesr/edp-audits)
- **Research runtime:** [edp_v5](https://github.com/devBorgesr/edp_v5)
- **Research / retrieval diagnostics:** [lab_edp](https://github.com/devBorgesr/lab_edp)
