🧬 Finding New Drug Molecules from PubMed Abstracts

I collaborated on this study with my final-term pharmacy students, 🔬Ali Levent Buldu. They actively contributed by writing code, performing data cleaning, and assisting with model assessments using JupyterLab.

In this project, we apply Natural Language Processing (NLP) and machine learning techniques to analyze scientific literature from PubMed, aiming to identify meaningful patterns and insights for drug discovery. The workflow includes data collection, text preprocessing, feature extraction, model development, and visualization of results.

Key Highlights:

🔍 NLP applied to biomedical abstracts spanning 5 years (2020–2025)

🧠 Machine learning models built in Python using Jupyter Lab

📊 Data filtering, transformation, and visualization for trend analysis

💡 Preliminary findings to support pharmaceutical and biomedical research

🔄 Fully reproducible pipeline shared via GitHub

Observations:
• Cancer and Tumor have the largest number of cases with a positive effect, with 139 and 137 occurrences, respectively.
• Parkinson appears to have no negative effect entries, but only a small number (7) with a positive effect.
• Diseases like Alzheimer, Arthritis, and Leukemia also show a significant portion of positive effect entries.
• Infection, Diabetes, and Leukemia have relatively low counts of diseases with positive effects compared to others.


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
