# ⚖️ Claims Ledger

> Not "what to read" but "what has actually been established." Each row tracks a contested or load-bearing claim in our field and its current evidence state.
> Statuses: ✅ replicated · ⚔️ contested · 🔬 under test · 💤 untested. Updated when papers enter our experiments — not on a schedule.

| Claim | Status | Evidence for | Evidence against / caveats |
|---|---|---|---|
| Synthetic data alone protects against membership inference | ⚔️ contested | DP-guaranteed synthesis: [Tab-PE — Differentially Private Synthetic Tabular Data via Private …](https://openreview.net/forum?id=SPgqHr2jiK) · [Minimax optimal differentially private synthetic data for smooth qu…](http://arxiv.org/abs/2602.01607v3) | *Finding Connections* — MIA succeeds in multi-table settings |
| Deduplicating training data improves LM quality | ✅ replicated | [Deduplicating Training Data Makes Language Models Better](https://arxiv.org/abs/2107.06499) · adopted by [The FineWeb Datasets: Decanting the Web for the Finest Text Data at…](https://arxiv.org/abs/2406.17557) | — |
| Foundation models can be pretrained on synthetic data alone | 🔬 under test | [CauKer: Classification Time Series Foundation Models Can Be Pretrai…](https://openreview.net/forum?id=xBW2FIfswU) (time-series classification) | Open beyond time-series |
| DP training necessarily destroys utility at practical ε | ⚔️ contested | Trade-off is real: [Deep Learning with Differential Privacy](https://arxiv.org/abs/1607.00133) | [The Adverse Effects of Omitting Records in Differential Privacy: Ho…](http://arxiv.org/abs/2601.05180v2) — the sampling story is subtler; adaptive schemes narrow the gap |
| Robustness must trade off accuracy | ⚔️ contested | [Theoretically Principled Trade-off between Robustness and Accuracy …](https://arxiv.org/abs/1901.08573) formalizes the tension | [Robustness of Mixtures of Experts to Feature Noise](http://arxiv.org/abs/2601.14792v2) — architecture can shift the frontier |

<sub>Last reviewed: 2026/07 · maintained alongside CUBIG's internal experiment ledger.</sub>
