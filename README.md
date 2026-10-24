## Hi, I am Nasir 👋

I build **clinical genomics pipelines**, from raw sequencing reads to benchmarked variant calls and finished clinical reports, plus machine learning on genomic and microbial data.

- MSc Bioinformatics, University of Birmingham (Thesis: Interpretable ML for multidrug resistance in *K. pneumoniae*)

- BSc Clinical Microbiology + a decade of clinical lab experience

- Open to clinical bioinformatics roles in Türkiye (Ankara): clinical genetics, molecular pathology, public-health microbiology

### Clinical Genomics

Every pipeline is benchmarked against public truth sets (GIAB, SEQC2) and generates a clinical-style PDF report. All data are public or simulated; no patient data.

| Repo | Topic | Stack | Description |
|---|---|---|---|
| [germline-wgs-giab](https://github.com/nesirli/germline-wgs-giab) 🚧 | Germline WGS | Nextflow, Docker, BWA-MEM2, GATK, DeepVariant, hap.py, VEP, Exomiser | FASTQ to ACMG-classified variants, benchmarked on GIAB HG001–HG007 |
| [trio-denovo-giab](https://github.com/nesirli/trio-denovo-giab) 🚧 | Trio analysis | Nextflow, GATK joint calling, somalier, slivar, RTG Tools | De novo and inheritance analysis on both GIAB trios, with relatedness QC |
| [roh-recessive-wes](https://github.com/nesirli/roh-recessive-wes) 🚧 | Consanguinity / ROH | Nextflow, AutoMap, bcftools roh, BAMSurgeon, Exomiser | Finding homozygous recessive variants inside runs of homozygosity in singleton exomes |
| [somatic-tumor-benchmark](https://github.com/nesirli/somatic-tumor-benchmark) 🚧 | Somatic cancer | Nextflow, Mutect2, CNVkit, MSIsensor-pro, som.py, VEP, CIViC | Tumour/normal and tumour-only calling, TMB/MSI and AMP/ASCO/CAP tiering, benchmarked on SEQC2 and GIAB HG008 |
| [cnv-acmg-scoring](https://github.com/nesirli/cnv-acmg-scoring) 🚧 | CNV | Nextflow, CNVnator, Manta, GATK gCNV, truvari, ClassifyCNV | CNV calling with ACMG/ClinGen 2020 scoring, benchmarked on GIAB HG002 SVs |
| [ag-report](https://github.com/nesirli/ag-report) 🚧 | Reporting | Python, Jinja2, WeasyPrint | Shared engine that turns pipeline outputs into clinical-style PDF reports |

### Microbial Genomics

| Repo | Topic | Stack | Description |
|---|---|---|---|
| [bacterial-wgs-amr](https://github.com/nesirli/bacterial-wgs-amr) 🚧 | Bacterial WGS / AMR | Nextflow, nf-core/bacass, AMRFinderPlus, chewBBACA, ECTyper, GrapeTree | Typing, AMR prediction vs lab phenotypes and cgMLST outbreak clustering for *E. coli* ST131 |
| [sa-amr-ml](https://github.com/nesirli/sa-amr-ml) 🚧 | Microbial Genomics, Machine Learning | Python, uv, GNU Make, NCBI Datasets, AMRFinderPlus, PyTorch, Hugging Face Transformers, DNABERT-2, LoRA, XGBoost | Erythromycin resistance prediction in *Staphylococcus aureus*: fine-tuned DNABERT-2 vs XGBoost on gene features |

### Toolbox

**Genomics:** WGS/WES analysis, germline and somatic variant calling, CNV/SV, trio and ROH analysis, bacterial assembly and typing, AMR tools

**Clinical interpretation:** ACMG/AMP, ClinGen CNV (2020), AMP/ASCO/CAP somatic tiers, CPIC pharmacogenomics, EUCAST

**Benchmarking:** GIAB, SEQC2, hap.py, som.py, truvari

**ML:** PyTorch, Hugging Face Transformers, DNABERT-2, scikit-learn, XGBoost, Optuna, SHAP

**Engineering:** Python, Nextflow, Snakemake, Docker, conda/mamba, uv, pytest, GitHub Actions

### Writing

I write about bioinformatics and machine learning at [nasirnesirli.com](https://nasirnesirli.com)
