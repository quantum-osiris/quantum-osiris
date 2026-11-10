# Devin Phillip Davis

**Independent Researcher | Agile Defense Systems LLC**

*Governed AI Systems · Quantum Control · Artificial Life · Reproducible Research*

I design and investigate **local-first, governed AI systems** and conduct small-scale, pre-registered experiments in quantum control, adaptive computation, and artificial life.

My research focuses on a common question: **How can adaptive systems explore, learn, and evolve while remaining measurable, reproducible, and subject to explicit constraints?**

Across projects, I separate probabilistic intelligence from deterministic authority. Models and adaptive algorithms may generate proposals, but independently defined rules govern authorization, execution, measurement, and evidence collection.

## Research Principles

**Falsifiability by design.** Experiments define hypotheses, evaluation procedures, and pass/fail criteria before execution. Negative results are preserved rather than discarded.

**Deterministic governance.** Adaptive systems operate within explicit capability boundaries. Proposed actions are evaluated against defined policies before execution.

**Evidence over assertions.** Results are evaluated against pre-established criteria and recorded as **PASS** or **FAIL** in scorecards derived from raw experimental artifacts.

**Reproducibility and provenance.** Experimental configurations, execution records, and supporting artifacts are maintained to enable independent inspection and replication.

**Persistent research artifacts.** Software releases are archived through Zenodo with persistent Digital Object Identifiers (DOIs).

## Research Repositories

| Repository | Research focus | Archive |
|---|---|---|
| [**osiris-cli**](https://github.com/quantum-osiris/osiris-cli) | Governed, local-first AI console investigating conversational learning in small language models. Models propose; deterministic software authorizes, evaluates, and records outcomes. | [Zenodo](https://doi.org/10.5281/zenodo.24082031) |
| [**dnalang-core**](https://github.com/quantum-osiris/dnalang-core) | **dna::}{::lang**, a domain-specific language for quantum-circuit families. Supports Aer/IBM backends, evolutionary optimization of dynamical-decoupling sequences, and write-ahead execution records. | [Zenodo](https://doi.org/10.5281/zenodo.22862567) |
| [**organism_sim**](https://github.com/quantum-osiris/organism_sim) | Artificial-life research involving rule-evolving agents, XCS learning classifier systems, and pre-registered experimental benchmarks. | [Zenodo](https://doi.org/10.5281/zenodo.22862567) |
| [**bridge**](https://github.com/quantum-osiris/bridge) | Integrates the organism_sim adaptive controller with dnalang-core's quantum-control search space, combining simulator ground truth with linked experimental provenance. | [Zenodo](https://doi.org/10.5281/zenodo.22862567) |
| [**osiris-governance**](https://github.com/quantum-osiris/osiris-governance) | Deterministic capability-governance framework separating model-generated proposals from policy authorization and fail-closed execution. | — |

## Shared Technical Direction

These projects explore complementary aspects of controlled adaptive computation:

- **Intelligence:** Learning, reasoning, evolutionary search, and adaptive decision-making.
- **Governance:** Explicit permissions, deterministic policy evaluation, and bounded execution.
- **Experimentation:** Pre-registered criteria, reproducible benchmarks, and negative-result reporting.
- **Provenance:** Traceable configurations, execution evidence, and independently inspectable results.

The objective is not to assume that adaptive behavior constitutes learning or improvement, but to establish **whether measurable improvement occurs under defined experimental conditions**.

## Repository Migration and Continuity

In November 2026, these repositories were migrated to the [quantum-osiris](https://github.com/quantum-osiris) organization following loss of access to the previous GitHub accounts:

- `github.com/osiris-dnalang`
- `github.com/devinphillipdavis`

The repositories retain their original Git commit histories. Existing commit hashes therefore continue to identify the same committed content, and previously published Zenodo DOIs remain associated with their archived research artifacts.

This migration reflects an account-access change, not a restart of the underlying research.

## Collaboration and Independent Replication

Independent replication, methodological criticism, benchmark comparisons, and technically grounded collaboration are welcome.

For questions, replication results, reproducibility issues, or proposed improvements, please open an issue in the relevant repository.

**Research standard:** Define the claim. Establish the test. Execute within constraints. Preserve the evidence. Report the result—even when it fails.
