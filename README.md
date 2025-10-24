# IRl AKl Signatures_Code

This repository contains the scripts and model files used to analyze the GEO datasets GSE126805 and GSE90865, aiming to study the immune signatures of ischemia-reperfusion associated acute kidney injury (IRl AKl).

## Directory Structure
IRl AKl Signatures_Code/
├── 1-GEO/              # Scripts for downloading and preprocessing GEO data
├── 2-Difference/       # Scripts for differential expression analysis
├── 3-Compare/          # Scripts for data comparison analysis
├── 4-GOKEGG/           # Scripts for GO and KEGG enrichment analysis
├── 5-model/            # Scripts for model construction and validation
├── 6-nomogram/         # Scripts for nomogram construction
├── 7-CIBERSORT-disease/ # Scripts for applying CIBERSORT algorithm
├── input/              # Input data folder
│   ├── .RData           # R data file
│   ├── .Rhistory        # R history file
│   ├── 1-GEOData        # RStudio project file
│   ├── data_trans       # Data transformation script
│   └── GEO_RNASSEQ      # RNA-seq data script
└── README.md           # This README file

## Usage Instructions

1. **Environment Preparation**
   - Ensure R and Python environments are installed.
   - Install required R packages and Python libraries.

2. **Data Download**
   - Run the scripts in the `1-GEO` folder to download and preprocess GEO datasets.

3. **Differential Expression Analysis**
   - Run the scripts in the `2-Difference` folder to perform differential expression analysis.

4. **Data Comparison**
   - Run the scripts in the `3-Compare` folder to perform data comparison analysis.

5. **Enrichment Analysis**
   - Run the scripts in the `4-GOKEGG` folder to perform GO and KEGG enrichment analysis.

6. **Model Construction**
   - Run the scripts in the `5-model` folder to construct and validate models.

7. **Nomogram Construction**
   - Run the scripts in the `6-nomogram` folder to construct nomograms.

8. **CIBERSORT Algorithm Application**
   - Run the scripts in the `7-CIBERSORT-disease` folder to apply the CIBERSORT algorithm.

## Dependency Libraries

- **R Packages**:
  - dplyr
  - tidyr
  - edgeR
  - DESeq2
  - clusterProfiler
  - org.Hs.eg.db
  - CIBERSORT

- **Python Libraries**:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn

## License

This project is licensed under the MIT License. See the LICENSE file for details.
