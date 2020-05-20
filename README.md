# Splice-Site-Prediction
Prediction of Splice Sites for Human and Elegans DNA.  
This work was part of a project for the course 'Machine Learning For Health Care' at ETH Zurich and was done by Rafael Bischof and Levin Moser.

## Overview
The 'elegans_splice_site_prediction.ipynb' contains mutiple models to predict Splice sites in C. Elegans DNA strings. 

### Install the Conda environment 
```console
conda env create -f ml4hc.yml
conda activate ml4hc
```

## Download the Data
Download the zip file from https://polybox.ethz.ch/index.php/s/OUZmQBskMA4zXND and unzip it. Copy the 'data' sub-directory into the repository folder.  
Your folder structure should look the following:

```
Splice-Site-Prediction
│   README.md
│   ...
└───data
│      C_elegans_acc_seq.csv
│      human_dna_test_hidden_split.csv
│      ...
```

### Run the notebooks
```console
jupyter notebook elegans_splice_site_prediction.ipynb
```