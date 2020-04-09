# Drug-Target Interaction

## 2020, Machine learning and AI-based approaches for bioactive ligand discovery and GPCR-ligand recognition

**Goal**:  Identifying candidate molecules for more elaborate bioactivity assays

Approaches for computer-aided ligand discovery

* Ligand-based: given the hypothesis that similar molecules are likely to bind the target receptor and exhibit a certain level of bioactivity.
* Structured-based: assumes knowledge of the receptor structure with molecular docking being one of the most prominent structure-based.

Machine Learning Uses in DTI:

* discovery of novel drug targets and ligands
* bioactivity prediction
* predicting new binding sites in GPCRs
* analyzing the association between the drug targets and diseases
* studying binding pathways
* optimizing lead compounds
* molecular de novo design
* developing biomarkers to assess the efficacy of drugs

Molecular Representation Methods:

* Property-based feature vectors (2D molecular fingerprints - ECFP)
* SMILES
* 3D voxels
* Graph representation

Free Datasets:

* **MoleculeNet** large benchmark dataset consisting of more than 700,000 molecules and their property annotation
* **ChEMBL** large-scale bioactivity database contains more than 5.4 million bioactivity measurements for 5,200 protein targets and more than 1 million ligands
* **Tox 21** dataset contains 8,000 compounds labeled as active or inactive for 12 proteins
* **GPCR structures** relatively small

Other available datasets (not mentioned):

* **DrugBank**
* **Drug Target Common (DTC)**
* **BioSNAP** drug-target interaction network that contains information on which genes (i.e., proteins encoded by genes) are targeted by drugs that are on the U.S. market (Stanford by Jure Leskovec)


## 2017, Deep learning-based drug-target interaction prediction

Computational Approaches:

* Ligand-based: apply quantitative structure-activity relationship (QSAR) to predict the bioactivity of a molecule on a target. QSAR is based on hypothesis that molecules with similar structure have similar bioactivity
* Structure-based: i.e. molecular docking, uses the crystallographic structure of target to screen the small molecules

Used datasets:

* **DrugBank**
* Data available as [https://github.com/Bjoux2/DeepDTIs](https://github.com/Bjoux2/DeepDTIs)


## 2020, Predicting commercially available antiviral drugs that may act on the novel coronavirus (2019-nCoV), Wuhan, China through a drug-target interaction deep learning model

> Molecule transformer-drug target interaction (MT-DTI) was used to predict binding affinity values between commercially available antiviral drugs and target proteins. Briefly, the natural language
processing (NLP) based Bidirectional Encoder Representations from Transformers (BERT) framework is a core algorithm of the model with good performance and robust results in diverse drug-target
interaction datasets through pretraining with ‘chemical language’ SMILES of approximately 1,000,000,000 compounds.

Training ...
> To train the model, the Drug Target Common (DTC) database (11) and BindingDB (12) database were manually curated and combined. Three types of efficacy value, Ki, Kd, and IC50 were integrated by a consistence-score-based averaging algorithm (13) to make the Pearson correlation score over 0.9 in terms of Ki, Kd, and IC50. Since the BindingDB database includes a wide variety of species and target
proteins, the MT-DTI model has the potential power to predict interactions between antiviral drugs and 2019-nCoV proteins.

Free Datasets:

* **NCBI** National Center for Biotechnology Information (NCBI) database
* **BindingDB** [https://www.bindingdb.org/bind/chemsearch/marvin/SDFdownload.jsp?all_download=yes](https://www.bindingdb.org/bind/chemsearch/marvin/SDFdownload.jsp?all_download=yes)