
# 📦 Projet de Prédiction du Prix des Smartphones

Ce projet inclut :
- ✅ Entraînement d’un modèle de régression sur le **prix log-transformé**
- ✅ Comparaison de 3 modèles (Random Forest, Gradient Boosting, Extra Trees)
- ✅ Tuning automatique du meilleur modèle
- ✅ Application Streamlit en USD uniquement, avec visualisation dynamique

## 🧪 Fichiers inclus

- `retrain_model_clean_full_models.py` : script complet d'entraînement + sélection automatique
- `app_streamlit_usd_visuals.py` : application Streamlit (prévision + visualisations)
- `ndtv_data_final.csv` : jeu de données original

## 💵 Conversion
Tous les prix sont en **USD** avec la conversion : `1 USD = 86.14 ₹`.

## 📈 Visualisation
Un graphique `Prix réel vs Prix prédit` est généré automatiquement dans l’onglet 2.

## ▶️ Lancement
```bash
streamlit run app_streamlit_usd_visuals.py
```

Entraînez d'abord le modèle via :
```bash
python retrain_model_clean_full_models.py
```

