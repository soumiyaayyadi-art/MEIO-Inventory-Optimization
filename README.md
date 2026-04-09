# 📦 MEIO — Inventory Optimization
## Multi-Echelon Inventory Optimization using SimPy & scipy

**SCM & Intelligence Artificielle — Master M1**  
Université Abdelmalek Essaâdi / FSJESTe · Spring 2026

---

## 👥 Groupe
- Soumaya Ayyadi
- Salma Anakar  
- Hajar Oujar

**Encadrant :** Yassine Tabaa, PhD, Ing

---

## 🎯 Problématique
Optimiser les stocks de sécurité d'un réseau de distribution 
à 2 échelons (1 DC → 3 magasins) sous demande stochastique.  
Objectif : minimiser les coûts de holding tout en maintenant 
un niveau de service cible (90%, 95%, 99%).

---

## 🗂️ Structure du repo

| Fichier | Description |
|---------|-------------|
| `MEIO_Inventory_Optimization.ipynb` | Notebook principal (simulation + optimisation) |
| `Rapport_MEIO_Ayyadi_Anakar_Oujar.docx` | Rapport scientifique format IEEE |
| `network_supply_chain.png` | Visualisation du réseau NetworkX |
| `stock_evolution.png` | Evolution journalière des stocks |
| `resultats_finaux.csv` | Tableau comparatif des résultats |

---

## ⚙️ Tech Stack
- Python 3.11
- SimPy 4.1.1 — Simulation par événements discrets
- scipy.optimize — Optimisation convexe (SLSQP)
- NumPy / Pandas — Calculs et tableaux
- NetworkX — Visualisation du réseau
- Plotly / Matplotlib — Graphiques

---

## 📊 Résultats clés

| Politique | Coût Total | Fill Rate | Economie |
|-----------|-----------|-----------|---------|
| Baseline (s,Q) | $1,201,625 | 99.8% | --- |
| MEIO 90% | ~$822,500 | 90.2% | -31.6% |
| MEIO 95% | ~$950,800 | 95.1% | -20.9% |
| MEIO 99% | ~$1,100,150 | 99.0% | -8.5% |

---

## 🚀 Comment exécuter

```bash
pip install simpy numpy scipy pandas matplotlib networkx plotly
jupyter notebook MEIO_Inventory_Optimization.ipynb
```
Exécuter toutes les cellules dans l'ordre (Shift + Enter).

---

## 🤖 Utilisation des outils IA
L'IA (Claude - Anthropic) a été utilisée pour l'assistance 
au développement du code et à la rédaction du rapport.  
Voir la section dédiée dans le rapport IEEE pour les détails.
