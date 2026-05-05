# Hi, I'm Matthew Ng

I'm a bioinformatics and computational biology developer interested in building reproducible pipelines, machine learning workflows, and data-driven tools for biological and clinical research.

My work sits at the intersection of genomics, single-cell analysis, nanopore signal processing, and applied machine learning. I like projects that turn complex datasets into interpretable results, especially when the workflow is documented well enough for someone else to run, inspect, and extend.

## Featured Projects

### [scRNA Scanpy and Seurat Comparison Pipeline in Nextflow](https://github.com/ngmattt/scRNA-Scanpy-and-Seurat-comparison-pipeline-in-Nextflow)

A reproducible Nextflow workflow for comparing single-cell RNA-seq analysis across Scanpy and Seurat using the same PBMC dataset.

**Focus:** single-cell RNA-seq, workflow automation, framework comparison, reproducible analysis  
**Tools:** Nextflow, Python, R, Scanpy, Seurat, Docker, Conda

- Built a parallel Scanpy and Seurat workflow from shared inputs.
- Included preprocessing, QC, doublet detection, clustering, UMAP visualization, marker discovery, and cell type annotation.
- Compared framework outputs through cluster correspondence, differential expression overlap, cell type composition, interferon-response recovery, and pseudobulk feasibility reporting.
- Used the public GSE96583 PBMC dataset from Kang et al. as the default analysis dataset.

### [m1A RNA Modification Prediction from Raw Nanopore RNA004 Signal Data](https://github.com/ngmattt/m1A-RNA-modification-prediction-using-raw-nanopore-RNA-004-signal-data)

An end-to-end machine learning workflow for predicting N1-methyladenosine (m1A) RNA modification sites from Oxford Nanopore direct RNA signal-derived features.

**Focus:** RNA modification prediction, nanopore signal analysis, site-level modeling, machine learning  
**Tools:** Python, Nextflow, XGBoost, Random Forest, CatBoost, scikit-learn, pandas, f5c, Dorado

- Designed a site-level prediction strategy using aggregated nanopore events aligned to genomic or transcriptomic positions.
- Engineered event-level and site-level features from raw signal-derived tables.
- Used site-aware train/test splitting to reduce read-level leakage.
- Compared XGBoost, Random Forest, and CatBoost models, with CatBoost reaching the strongest held-out performance across accuracy, F1, AUROC, and AUPRC.
- Added a portable Nextflow workflow alongside the original script-based workflow.

### [U-Net Segmentation and Classification for Predicting Fixed Orthodontic Appliances](https://github.com/ngmattt/U-Net-Segmentation-and-Classification-for-Predicting-Fixed-Orthodontics-Appliances)

A two-stage computer vision and machine learning workflow for detecting and classifying fixed orthodontic appliances from dental radiograph images.

**Focus:** medical image segmentation, feature extraction, classification, model evaluation  
**Tools:** Python, Jupyter Notebook, U-Net, Logistic Regression, Random Forest, Decision Tree, KNN, SVM

- Used a U-Net convolutional neural network to generate pixel-level segmentation masks.
- Extracted downstream features from segmented orthodontic regions, including FOA area and percent FOA area.
- Evaluated multiple classification models using ROC curves, learning curves, and summary statistics.
- Structured the repository around reproducible analysis while keeping private image datasets out of version control.

## Technical Interests

- Single-cell RNA-seq analysis
- Bioinformatics workflow development
- RNA modification prediction
- Nanopore sequencing signal analysis
- Machine learning for biological and clinical datasets
- Medical image segmentation and classification
- Reproducible research with Nextflow, Docker, and Conda

## Tools and Technologies

**Languages:** Python, R, SQL, Bash, HTML, CSS  
**Bioinformatics:** Scanpy, Seurat, Nextflow, f5c, Dorado, minimap2, samtools  
**Machine Learning:** scikit-learn, XGBoost, CatBoost, Random Forest, U-Net, model evaluation workflows  
**Data:** pandas, NumPy, Jupyter Notebook, MySQL, SQLite  
**Workflow and Dev Tools:** Git, GitHub, Docker, Conda, VS Code

## Other Work

- [HPV and Genital Warts Database](https://github.com/ngmattt/HPV-and-Genital-Warts-Database): MySQL and Django-based web interface for integrating epidemiological and geographic HPV data.
- [Longitudinal OMOP Phenotyping](https://github.com/ngmattt/Longitudinal-OMOP-phenotyping): Unsupervised learning workflow for discovering longitudinal lab-derived patient phenotypes.
- [High Throughput Data Analysis](https://github.com/ngmattt/High-Throughput-Data-Analysis): Bioinformatics coursework and analysis workflows.

## What I'm Building Toward

I'm continuing to develop projects that combine biological questions with reproducible software engineering. My goal is to build analysis pipelines and machine learning systems that are not only accurate, but also transparent, well-documented, and useful to researchers.

## Connect

- GitHub: [github.com/ngmattt](https://github.com/ngmattt)
- LinkedIn: [Add your LinkedIn URL here](https://www.linkedin.com/)
- Email: Add your email here
