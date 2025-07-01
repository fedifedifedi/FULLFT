
# FULLFT - Analyse de Sentiment avec DistilBERT

Projet d'analyse de sentiment utilisant DistilBERT fine-tuné sur le dataset IMDB, avec une interface web Streamlit.

## Fonctionnalités

- Fine-tuning d’un modèle DistilBERT pré-entraîné
- Interface web interactive avec Streamlit
- Sauvegarde du modèle local

## Fichiers principaux

- `fine_tune_simple.py` : script d'entraînement du modèle
- `AppTest.py` : interface web Streamlit

## Dépendances

- Python 3.8+
- Transformers
- Datasets
- Streamlit
- Torch

## Lancer l'application

```bash
streamlit run AppTest.py
