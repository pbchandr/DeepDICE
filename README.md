# BipodNet/BipodNN

BipodNet/BipodNN is a multi-view **B**iology **I**nduced Neural **Net**work for **P**rediction **o**f **D**isease Phenotypes. It uses multi-modal data in the form of rna-seq and genotype data to predict Schizophrenia samples. The intermediate layer is a biologival masking gene layer in the form of EQTL and Gene Regulatory Network (GRN). We hypothesise that introducting biology will help in better phenotypic prediction and also helps in understanding the disease mechanisms better.


## Data
All sample data can be accessed [here](https://uwmadison.box.com/s/as518bcuttpkdonads64iriqfdd1aixl)

If you have your own data, please use the following guide to prepare the data.

### Preparing RNA-seq data
The cript requires a csv file that contains gene expression data where the rows are the samples and the columns are the genes

### Preparing Genotype data
The model uses the dosage information for SNP coordinates. The rows are the samples  and the columns are the SNP dosage information.

### Preparing intermediate layer
Gene Regulatory Network (GRN) and eQTL-gene linkage are used as the biologial masking intermediate layer that guides the activation units in the neural network model.
