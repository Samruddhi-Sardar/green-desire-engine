# 🌱 Sustainable Prestige: Predicting Luxury Car Buyer Behaviour

This repository contains the code, visuals, and analysis for my MSc dissertation at the University of Southampton (2025).

## 🎯 Project Overview
The *Sustainable Prestige* is an AI toolkit designed to forecast adoption of eco-innovations in the luxury automotive sector (e.g., vegan leather, solar roofs, recycled materials).  

- Collected and processed multi-source consumer discourse (reviews, forums, brand comms, news).  
- Tagged sustainability features via hybrid rules + context classifier.  
- Estimated sentiment and stance using FinBERT with confidence weighting.  
- Built brand × feature adoption signals combining stance, sentiment, and discourse momentum.  
- Trained predictive models (LightGBM, Ridge regression, Graph Neural Networks).  
- Conducted ablation studies to identify discourse momentum and brand anchoring as key adoption drivers.  

## 📂 Repository Contents
- `notebooks/` – Jupyter notebooks with preprocessing, NLP, and ML experiments.  
- `src/` – Clean Python scripts for the adoption model and ablation tests.  
- `results/` – Figures, tables, and performance metrics.  
- `docs/` – Methodology diagrams and visuals.  

## 🛠️ Tech Stack
- **Languages:** Python (pandas, NumPy, scikit-learn, PyTorch Geometric)  
- **NLP Models:** FinBERT, domain transformers  
- **ML Models:** LightGBM, Ridge Regression, Graph Neural Networks  
- **Other Tools:** Matplotlib, Seaborn, Colab, GitHub  

## 📊 Key Results
- Full model rank correlation: ρ = 0.37  
- Removing mentions collapsed rank correlation to ρ = 0.06 → proves volume is critical  
- Brand anchoring essential (ρ ≈ 0.01 when stripped)  
- Minimal model (brand + feature IDs only) achieved ρ = 0.62  

## 📄 Dissertation
University of Southampton – MSc Business Analytics & Management Science (2025).  

---

🚀 *This project bridges academic rigour and managerial insights, highlighting how predictive analytics can support ESG strategy in luxury automotive.*
