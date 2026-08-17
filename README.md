# Nasir Nesirli

**- ML for microbial genomics (AMR prediction WGS)**

**- Deep learning on genomic sequence (DNA language models).**

I spent 10 years running clinical diagnostic laboratories, watching patients wait 72 hours for culture results while doctors guessed at antibiotics. Now I build the tools I wished I had back then: interpretable machine learning on bacterial genomes.

- 🧬 MSc Bioinformatics, University of Birmingham — thesis on interpretable ML for multidrug resistance in *K. pneumoniae*
- 🔬 BSc Clinical Microbiology + a decade of clinical lab leadership (PCR/molecular diagnostics, 26-site network)
- 📍 Ankara, Türkiye (UTC+3) · open to remote contracts (EU/US) · [nasirnesirli.com](https://nasirnesirli.com) · [LinkedIn](https://www.linkedin.com/in/nasirnesirli/)

## Flagship projects

**[klebsiella-amr](https://github.com/nesirli/klebsiella-amr)** — reproducible pipeline from raw Illumina reads to interpretable AMR predictions.
Raw FASTQs → fastp → Kraken2 → SPAdes → AMRFinderPlus → gene presence/absence features → XGBoost / LightGBM / PyTorch MLP (Optuna-tuned) → SHAP, permutation & occlusion interpretability. Optional DNABERT-2 sequence-level model. Temporal train/test splits, per-sample disk cleanup so thousands of genomes fit on a laptop, every model emitting the same six artifacts for honest comparison.

## Other projects

| Repo | What it is |
|---|---|
| [meta-scholar](https://github.com/nesirli/meta-scholar) | RAG question-answering over metagenomics literature |
| [diabetes-readmission](https://github.com/nesirli/diabetes-readmission) | Hospital readmission risk with modern ML engineering (tests, CI, packaging) |
| [stroke-risk](https://github.com/nesirli/stroke-risk) | Clinical risk prediction with interpretability |
| [ml-from-scratch](https://github.com/nesirli/ml-from-scratch) | ML algorithms implemented from first principles, documented |

## Toolbox

**Genomics:** WGS analysis, assembly, variant calling, AMR annotation (AMRFinderPlus), Kraken2, QC

**ML:** PyTorch, scikit-learn, XGBoost/LightGBM, Optuna, SHAP/LIME, DNABERT-2

**Engineering:** Python, Make/Snakemake/Nextflow, Docker, conda/mamba, pytest, GitHub Actions, AWS

## Writing

I write about AMR prediction, genomics ML/DL, and pipeline engineering at [nasirnesirli.com](https://nasirnesirli.com), 
shorter notes on [LinkedIn](https://www.linkedin.com/in/nasirnesirli/).

---

*Wet-lab reality, dry-lab tools.*
