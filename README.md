# Awesome Data-Centric & Trustworthy AI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Curated papers on **data-centric & trustworthy AI** — synthetic data, privacy, de-identification,
> adversarial robustness, hallucination, data quality, and more.
> 🤖 Auto-curated from an in-house paper-tracking pipeline (arXiv + HF Daily), human-verified before promotion.

**Legend**: `✅` human-verified · `🕓` auto-ingested (pending review). Each topic table is venue-first sorted.

## 🌱 Data-Centric
- [🗂️ Synthetic Data](collection/synthetic-data.md) (📖8+30)
- [🕵️ Privacy](collection/privacy.md) (📖8+30)
- [🏷️ De-identification & NER](collection/de-identification-ner.md) (📖8+30)
- [🧹 Data Preprocessing & Quality](collection/data-preprocessing.md) (📖7+6)
- [⚖️ Data-Centric vs Model-Centric](collection/data-centric-vs-model.md) (📖8+9)

## 🛡️ Trustworthy
- [🛡️ Adversarial Robustness](collection/adversarial-robustness.md) (📖8+30)
- [💭 Hallucination & Factuality](collection/hallucination-factuality.md) (📖8+11)
- [🎯 Safety & Alignment](collection/safety-alignment.md) (📖8+30)

## 📎 Meta
- [Surveys](meta/surveys.md) · [Tools](meta/tools.md) · [Benchmarks](meta/benchmarks.md)

## How it works
1. Pipeline appends new papers as `🕓` weekly.
2. A human reviews and promotes good ones to `✅`.
3. README Top Picks (below) show only `✅`.

## ⭐ Top Picks
One human-verified pick per topic — see each collection for the full `✅` set (103 total: 63 classics + 40 promoted).

- 🗂️ [TabStruct: Measuring Structural Fidelity of Tabular Data](collection/synthetic-data.md) — *ICLR 2026* · the benchmark to start with for synthetic-tabular evaluation
- 🕵️ [Auditing Apple's DifferentialPrivacy.framework](collection/privacy.md) — *IEEE S&P 2026* · what DP looks like (and breaks like) in production
- 🏷️ [De-Anonymization at Scale via Tournament-Style Attribution](collection/de-identification-ner.md) — *ACL 2026 Oral* · the threat model every anonymizer must face
- 🧹 [A Survey on Data Quality Dimensions and Tools for ML](collection/data-preprocessing.md) — *2024* · the map of the data-quality landscape
- ⚖️ [DataPerf: Benchmarks for Data-Centric AI Development](collection/data-centric-vs-model.md) — *NeurIPS D&B* · the canonical data-centric benchmark suite
- 🛡️ [The Shape of Adversarial Influence](collection/adversarial-robustness.md) — *ICLR 2026* · topological signatures of attacks in LLM latent space
- 💭 [Hallucination Begins Where Saliency Drops](collection/hallucination-factuality.md) — *ICLR 2026* · a mechanism-level account of why models hallucinate
- 🎯 [SafeDPO: Direct Preference Optimization with Enhanced Safety](collection/safety-alignment.md) — *ICLR 2026* · safety-constrained alignment without reward/cost models

> 📖 Each collection opens with a **Classics** table — 63 canonical pre-2026 papers (link-verified) — followed by the weekly auto-pipeline pool.

## Contributing
See [CONTRIBUTING.md](CONTRIBUTING.md). PRs welcome — format: `✓ | Title | Venue | Type | TL;DR`.

---
<sub>Maintained by [CUBIG](https://cubig.ai) · pilot 2026-07-23 · 239 papers (63 classics + 176 auto-curated)</sub>
