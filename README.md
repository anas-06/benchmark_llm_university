# Benchmark Multi-Critères des LLM (Master 1 I2A)

Ce dépôt contient une évaluation comparative de **GPT-4o**, **Mistral Large** et **Llama-3.3** basée sur le benchmark **MMLU-FR**.

## Objectifs du Projet
* **Évaluation Cognitive** : Mesurer la précision sur 57 sujets académiques.
* **Impact Environnemental** : Mesurer les émissions de CO2 via **CodeCarbon**.
* **Audit Éthique** : Détecter les biais et la toxicité via **Toxic-BERT**.

## Installation
1. Clonez le dépôt : `git clone https://github.com/votre-nom/votre-projet.git`
2. Installez les dépendances : `pip install -r requirements.txt`
3. Créez un fichier `.env` avec vos clés : `OPENAI_API_KEY`, `MISTRAL_API_KEY`, `GROQ_API_KEY`.

## Résultats Synthétiques
Les tests sur 100 questions montrent que **GPT-4o** domine en précision (83%) et en sobriété carbone (0.13g CO2), tandis que **Mistral Large** offre la meilleure latence (0.31s).
