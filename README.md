# TREC 88-90 Information Retrieval System

[![DOI](https://zenodo.org/badge/993399774.svg)](https://doi.org/10.5281/zenodo.17943727)
[![Buy me a coffee](https://img.shields.io/badge/Buy%20me%20a%20coffee-FFDD00?logo=buy-me-a-coffee&logoColor=black)](https://www.buymeacoffee.com/dominiqueloyer)
[![Sponsor on GitHub](https://img.shields.io/badge/Sponsor-DominiqueLoyer-EA4AAA?logo=github-sponsors)](https://github.com/sponsors/DominiqueLoyer)

**PhD Research Project** - Dominique S. Loyer  
*Citation Key: loyerEvaluationModelesRecherche2025*

---

## 📋 Overview

Information Retrieval system developed in Python with **Lucene** using the TREC 88-90 competition corpus containing **243,000 Associated Press articles** (1988-1990).

---

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/DominiqueLoyer/TREC_COMPETITION_88-90_AP.git
cd TREC_COMPETITION_88-90_AP

# Install dependencies
pip install numpy pandas pyserini

# Run the system
python main.py
```

---

## ✨ Features

- ✅ Lucene-based indexing and retrieval
- ✅ BM25 and TF-IDF ranking models
- ✅ Query expansion with RM3
- ✅ Porter stemming and stopword removal
- ✅ TREC evaluation metrics (MAP, NDCG, P@10)
- ✅ Integration with Pyserini

---

## 📊 Performance

| Model | MAP | NDCG@10 |
|-------|-----|---------|
| BM25 Baseline | 0.22 | 0.35 |
| BM25 + RM3 | **0.29** | **0.42** |

---

## 📁 Dataset

| Property | Value |
|----------|-------|
| Collection | TREC AP 88-90 |
| Documents | 243,000 |
| Source | Associated Press newswire |
| Years | 1988-1990 |
| Format | Standard TREC format |

---

## 📚 Related Publications

- *Évaluation de Modèles de Recherche d'Information*
- *Projet de création d'un moteur de recherche d'information avec Lucene*

---

## 🏷️ Citation

```bibtex
@software{loyer2025trec_competition,
  author = {Loyer, Dominique S.},
  title = {TREC 88-90 Information Retrieval System},
  year = {2025},
  publisher = {Zenodo},
  doi = {10.5281/zenodo.17943727},
  url = {https://github.com/DominiqueLoyer/TREC_COMPETITION_88-90_AP}
}
```

---

## 👤 Author

**Dominique S. Loyer**

- ORCID: [0009-0003-9713-7109](https://orcid.org/0009-0003-9713-7109)
- GitHub: [@DominiqueLoyer](https://github.com/DominiqueLoyer)
- Affiliation: Université du Québec à Montréal (UQAM)

---

## 📜 License

MIT License

---

**Last Updated:** January 2026
