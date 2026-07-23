# 🧭 Questions → Papers

> Practitioners start from a problem, not a topic. Each question descends into the papers that answer it — same pool as the topic collections, reorganized by entry point.

### How do I check whether my synthetic data actually preserves privacy?
- **Attack it (adversary's view)** → [Finding Connections](http://arxiv.org/abs/2602.07126v2) · [Membership Inference Attacks against Machine Learning Models](https://arxiv.org/abs/1610.05820)
- **Generate with DP guarantees instead** → [Tab-PE — Differentially Private Synthetic Tabular Data via Private …](https://openreview.net/forum?id=SPgqHr2jiK) · [Minimax optimal differentially private synthetic data for smooth qu…](http://arxiv.org/abs/2602.01607v3)
- **Use an evaluation framework** → [SynQP: A Framework and Metrics for Evaluating the Quality and Priva…](http://arxiv.org/abs/2601.12124v1)

### Should I spend my budget on more data or a bigger model?
- **Compute-optimal scaling** → [Training Compute-Optimal Large Language Models](https://arxiv.org/abs/2203.15556)
- **When data runs out** → [Scaling Data-Constrained Language Models](https://arxiv.org/abs/2305.16264)
- **Quality beats quantity** → [Beyond neural scaling laws: beating power law scaling via data prun…](https://arxiv.org/abs/2206.14486) · [Why Less is More (Sometimes): A Theory of Data Curation](https://openreview.net/forum?id=8KcjEygedc)

### How do I de-identify free-text (clinical) records?
- **Standard benchmark first** → [Automated systems for the de-identification of longitudinal clinica…](https://pubmed.ncbi.nlm.nih.gov/26225918/)
- **Neural de-id lineage** → [De-identification of Patient Notes with Recurrent Neural Networks](https://arxiv.org/abs/1606.03475) · [Deidentification of free-text medical records using pre-trained bid…](https://pmc.ncbi.nlm.nih.gov/articles/PMC8330601/)
- **Adaptive privacy-utility control** → [Adaptive Text Anonymization: Learning Privacy-Utility Trade-offs vi…](http://arxiv.org/abs/2602.20743v2)

### Which model family should I use for tabular synthesis?
- **GAN/VAE era** → [Modeling Tabular Data using Conditional GAN (CTGAN/TVAE)](https://arxiv.org/abs/1907.00503)
- **Diffusion era** → [TabDDPM: Modelling Tabular Data with Diffusion Models](https://arxiv.org/abs/2209.15421)
- **LLM / foundation-model era** → [Language Models are Realistic Tabular Data Generators (GReaT)](https://arxiv.org/abs/2210.06280) · [Using  maximal information auxiliary variables to improve synthetic…](https://openreview.net/forum?id=6PkiUAcTWF)

### Did my generative model memorize its training data?
- **Extraction attacks** → [Extracting Training Data from Large Language Models](https://arxiv.org/abs/2012.07805)
- **Memorization theory** → [What Drives the Inlier-Memorization Effect? A Theory of Outlier Det…](http://arxiv.org/abs/2606.29791v1)

### How do I evaluate synthetic time series beyond visual realism?
- **Evaluation-protocol origin** → [Time-series Generative Adversarial Networks (TimeGAN)](https://papers.nips.cc/paper_files/paper/2019/hash/c9efe5f26cd17ba6216bbe2a7d26d490-Abstract.html)
- **Backtest-grade generation** → [Beyond Visual Realism: Toward Reliable Financial Time Series Genera…](http://arxiv.org/abs/2601.12990v1)

### How do I make (and prove) a model robust to adversarial examples?
- **Adversarial training** → [Towards Deep Learning Models Resistant to Adversarial Attacks](https://arxiv.org/abs/1706.06083) · [Theoretically Principled Trade-off between Robustness and Accuracy …](https://arxiv.org/abs/1901.08573)
- **Certified guarantees** → [Certified Adversarial Robustness via Randomized Smoothing](https://arxiv.org/abs/1902.02918)
- **Evaluate honestly** → [Reliable evaluation of adversarial robustness with an ensemble of d…](https://arxiv.org/abs/2003.01690) · [RobustBench: a standardized adversarial robustness benchmark](https://arxiv.org/abs/2010.09670)

### How do I detect hallucinations in LLM output?
- **Sampling-consistency check** → [SelfCheckGPT: Zero-Resource Black-Box Hallucination Detection for G…](https://arxiv.org/abs/2303.08896)
- **Fine-grained factuality scoring** → [FActScore: Fine-grained Atomic Evaluation of Factual Precision in L…](https://arxiv.org/abs/2305.14251)
- **Benchmarks** → [TruthfulQA: Measuring How Models Mimic Human Falsehoods](https://arxiv.org/abs/2109.07958) · [HaluEval: A Large-Scale Hallucination Evaluation Benchmark for Larg…](https://arxiv.org/abs/2305.11747)

### How do I align an LLM without a full RLHF stack?
- **RL-free preference optimization** → [Direct Preference Optimization: Your Language Model is Secretly a R…](https://arxiv.org/abs/2305.18290)
- **AI-feedback alignment** → [Constitutional AI: Harmlessness from AI Feedback](https://arxiv.org/abs/2212.08073)
- **Safety-constrained variant** → [SafeDPO: A Simple Approach to Direct Preference Optimization with E…](https://openreview.net/forum?id=PJdw4VBsXD)

### Is my training data clean enough?
- **Label errors** → [Confident Learning: Estimating Uncertainty in Dataset Labels](https://arxiv.org/abs/1911.00068)
- **Duplicates** → [Deduplicating Training Data Makes Language Models Better](https://arxiv.org/abs/2107.06499)
- **Systematic validation** → [Data Validation for Machine Learning](https://proceedings.mlsys.org/paper_files/paper/2019/hash/928f1160e52192e3e0017fb63ab65391-Abstract.html)
- **A full modern recipe** → [The FineWeb Datasets: Decanting the Web for the Finest Text Data at…](https://arxiv.org/abs/2406.17557)

