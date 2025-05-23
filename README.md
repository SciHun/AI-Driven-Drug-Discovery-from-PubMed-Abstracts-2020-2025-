🧬 Finding New Drug Molecules from PubMed Abstracts

This project uses NLP and biomedical databases to extract potential novel drug molecules from PubMed abstracts.

🔍 Project Pipeline
1. **Data Collection** – PubMed API (Entrez)
2. **Preprocessing** – Text cleaning and tokenization
3. **NER** – Using SciSpacy, BioBERT, or PubChemNER
4. **Filtering** – Remove known drugs (DrugBank/ChEMBL)
5. **Context Analysis** – Keep only positive-effect mentions
6. **Result Storage** – Save filtered molecules and metadata
7. **Visualization** – Disease-wise molecule insights
📁 Folders

- `notebooks/`: Jupyter notebooks
- `src/`: Core Python scripts
- `figures/`: Graphs and charts (e.g., confusion matrix, top molecules)
- `results/`: Final CSV outputs

## 📦 Requirements
See `requirements.txt`


## 💡 Authors
🔬Harun Un, PhD – Clinical Biochemist & Data Scientist  
🔬Ali Levent Buldu, BSc – Pharmacist
