# Scientific Paper Library

Assistant RAG pour interroger une bibliothèque d'articles scientifiques (arXiv, domaine NLP et LLM) en langage naturel, avec des réponses sourcées et vérifiables.

**Groupe :** Charfeddine Farah, Khalifa Ranim, Jleili Asma, Ben Radhia Chaima

Cahier des charges : [`docs`](docs/)

## Fonctionnalités

- Ingestion d'articles arXiv avec métadonnées et mise à jour incrémentale
- RAG avec citations (article, page, passage)
- Serveur MCP (`add_paper`, `search_library`, `summarize_collection`)
- Workflow LangChain et LangGraph
- Interface web
- Fine-tuning d'un modèle d'embeddings comparé au modèle de base
- Benchmarking : Recall@k et MRR sur au moins 50 questions

## Structure du dépôt

```
docs/            cahier des charges, rapport technique
data/            données locales (PDF non versionnés)
src/ingestion/   téléchargement arXiv, extraction PDF, indexation
src/rag/         recherche, génération avec citations, LangGraph
src/mcp_server/  serveur MCP et outils
src/finetuning/  fine-tuning des embeddings
src/evaluation/  métriques et script d'évaluation
src/app/         interface web
eval/            jeu d'évaluation (50 questions)
tests/           tests automatisés
notebooks/       expériences
```

## Installation

À compléter.

## Utilisation

À compléter.

## Résultats

| Configuration | Recall@1 | Recall@3 | Recall@5 | MRR |
|---|---|---|---|---|
| Embeddings de base | | | | |
| Embeddings fine-tunés | | | | |
