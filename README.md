# Welcome to RNA GENOMICS LAB 🧬🔬

## About Us
We are a bioinformatics organization focused on the study of **post-transcriptional immune system regulation**. Our work leverages high-throughput sequencing to decode the complex landscape of RNA dynamics, including alternative splicing, RNA editing, and mRNA stability within immune cell populations.

## 🔬 Research Areas
* **Post-transcriptional Landscapes:** Investigating how RNA processing shapes immune responses.
* **Immune System Profiling:** Analyzing RNA-seq data from T-cells, B-cells, and Macrophages under various stimuli.
* **Integrative Pipelines:** Developing reproducible workflows for RNA-seq, from raw reads to functional enrichment.


## 🛠️ Our Tech Stack
* **Languages:** `R` (Tidyverse, Bioconductor), `Python`, `Shell`.
* **Workflows:** `Nextflow` / `Snakemake`.
* **Tools:** `STAR`, `Salmon`, `DESeq2`, `DEXSeq`, `Seurat` (for scRNA-seq).
* **Environment Management:** `Conda`, `Docker`, `Singularity`.

## 📁 Repository Structure Standard
To ensure our computational experiments are reproducible, all repositories follow a standardized layout:

* **`data/`**: Configuration files, protein/ligand structures (PDB/SDF), and metadata. 
  *(Note: Large datasets like FASTQ or XTC trajectories are linked via external repositories like Zenodo or SRA).*
* **`scripts/`**: Core processing scripts (Python, R, Shell, or MDP files).
* **`notebooks/`**: Step-by-step analysis, Docking logs, and Exploratory Data Analysis.
* **`results/`**: Final figures (RMSD plots, Heatmaps), binding energy tables, and processed data.
* **`envs/`**: Conda `environment.yml` or Dockerfiles to replicate the exact computing environment.

## 🤝 Collaboration
We are open to collaborations. If you are interested in our datasets or pipelines, feel free to open an issue or reach out!

📫 **Contact:** [rodolfo.avilab@cinvestav.mx]
🌍 **Location:** [CDMX/CINVESTAV]
