#  Cheminformatics Pipeline for Drug Discovery (EGFR Target)

##  Overview
This project implements an end-to-end cheminformatics pipeline for screening and ranking drug-like molecules targeting EGFR using RDKit and machine learning.

##  Objectives
- Process molecular data from SMILES
- Identify drug-like compounds using Lipinski's Rule of Five
- Explore chemical space using clustering
- Build QSAR model to predict molecular activity
- Perform similarity search using Tanimoto coefficient
- Rank potential drug candidates

---

##  Workflow

SMILES → RDKit → Descriptors → Lipinski Filter → Clustering → QSAR Model → Similarity Search → Ranking

---

##  Tools & Technologies
- Python
- RDKit
- Pandas, NumPy
- Scikit-learn
- Seaborn, Matplotlib

---

##  Key Results

- Majority of compounds satisfied drug-likeness criteria
- Clustering revealed distinct chemical groups
- QSAR model identified top candidate molecules
- Similarity analysis enabled chemical space exploration

---

##  Project Structure


data/
notebooks/
results/


---

##  Applications
- Drug discovery screening
- Ligand prioritization
- Chemical space analysis

---

##  Author
Mimansa Kulshrestha
