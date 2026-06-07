# rdkit-molecular-descriptors
A cheminformatics pipeline built using RDKit to perform core drug  discovery workflows, including molecular descriptor calculation,  drug-likeness filtering, molecular fingerprint generation, chemical  similarity screening, and end-to-end virtual screening simulation. Built as part of preparation for computational drug discovery research.
## Background

Drug discovery is an expensive and time-consuming process — bringing 
a single drug to market takes an average of 12 years and over $2 
billion. Computational approaches, particularly machine learning-based 
virtual screening, have emerged as powerful tools to accelerate early 
stage drug discovery by predicting which molecules are likely to be 
effective before any lab experiment is performed.

At the heart of these computational approaches are molecular 
representations — numerical encodings of chemical structures that 
machine learning models can process. This project implements the 
foundational molecular representation techniques used in modern drug 
discovery pipelines: physicochemical descriptors, Lipinski filtering, 
Morgan fingerprints, and Tanimoto similarity scoring.

---

## What This Project Covers

- **Molecular Loading** — Parsing and visualising chemical structures 
  from SMILES string representations using RDKit
- **Descriptor Calculation** — Computing key physicochemical 
  properties including molecular weight, LogP, TPSA, H-bond 
  donors/acceptors, rotatable bonds, and aromatic ring count
- **Lipinski's Rule of Five** — Filtering compound libraries for 
  oral bioavailability and drug-likeness; identifying violations 
  per compound
- **Morgan Fingerprints** — Generating 2048-bit circular fingerprints 
  that encode local atomic environments; the most widely used molecular 
  representation in drug discovery ML models
- **Tanimoto Similarity** — Quantifying chemical similarity between 
  molecules using fingerprint-based comparison; core technique in 
  ligand-based virtual screening
- **Virtual Screening Pipeline** — End-to-end simulation of screening 
  a compound library against a query molecule, combining Lipinski 
  filtering and similarity ranking to identify top drug-like candidates

---

## Tools & Libraries

- Python 3
- RDKit
- NumPy
- Pandas
- Matplotlib

---

## How to Run

Open directly in Google Colab — no local setup required:

1. Click the `.ipynb` file above
2. Select **Open in Colab**
3. Run all cells in order
4. Cell 1 installs RDKit automatically

---

## Author

Haniya Junaid — B.Tech Biotechnology + Minor in Data Analytics  
Jaypee University of Information Technology, 2026  
[LinkedIn](https://linkedin.com/in/haniya-junaid) | 
[GitHub](https://github.com/haniyajuanidd)
