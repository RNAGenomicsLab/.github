# Welcome to RNA GENOMICS LAB 🧬🔬

## ## About Us
We are a bioinformatics organization dedicated to decoding **post-transcriptional immune system regulation** and molecular interactions. Our research leverages high-throughput sequencing and structural bioinformatics to explore RNA dynamics—including **alternative splicing and mRNA stability**—as well as protein-ligand interactions within immune cell populations.

## 🔬 Research Areas
* **Post-transcriptional Landscapes:** Investigating how RNA processing shapes immune responses.
* **Immune System Profiling:** Analyzing RNA-seq data from T-cells, B-cells, and Macrophages under various stimuli.
* **Structural Bioinformatics:** Utilizing **Molecular Docking** and **Molecular Dynamics (MD)** to study protein-target interactions and conformational changes.
* **Integrative Pipelines:** Developing reproducible workflows for RNA-seq and structural analysis, from raw data to functional insights.

## 🛠️ Our Tech Stack
* **Genomics & Transcriptomics:** `STAR`, `Salmon`, `DESeq2`, `DEXSeq`, `Seurat`.
* **Structural & Molecular Modeling:**
    * **Docking:** `AutoDock Vina`, `Open Babel`, `Meeko`.
    * **Dynamics:** `GROMACS`, `AMBER`, `MDAnalysis`.
    * **Visualization:** `PyMOL`, `ChimeraX`, `VMD`.
* **Languages:** `R` (Tidyverse, Bioconductor), `Python` (Biopython), `Shell`.
* **Workflows:** `Nextflow` / `Snakemake`.
* **Environment Management:** `Conda`, `Docker`, `Singularity`.

## 📁 Repository Structure Standard
To ensure our computational experiments are reproducible, all repositories follow a standardized layout:

* **`data/`**: Configuration files, protein/ligand structures (PDB/SDF), and metadata. 
  *(Note: Large datasets like FASTQ or XTC trajectories are linked via external repositories like Zenodo or SRA).*
* **`scripts/`**: Core processing scripts (Python, R, Shell, or MDP files for GROMACS).
* **`notebooks/`**: Step-by-step analysis, Docking logs, and Exploratory Data Analysis.
* **`results/`**: Final figures (RMSD plots, Heatmaps), binding energy tables, and processed data.
* **`envs/`**: Conda `environment.yml` or Dockerfiles to replicate the exact computing environment.
* **`docs/`**: Supplemental documentation, detailed protocols, and manual pages.

## 🤝 Collaboration
We are open to collaborations. If you are interested in our datasets, pipelines, or structural models, feel free to open an issue or reach out!

📫 **Contact:** [rodolfo.avilab@cinvestav.mx]
🌍 **Location:** [CDMX/CINVESTAV]
