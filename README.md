# Natural Language Processing (NLP) - Travaux pratiques

> **M2 Mathématiques et Informatique appliquées à la Science des Données (MIDS) - Université Paris Cité**  
> **Fatoumata NDOUR**

## Présentation

Ce dépôt rassemble des **travaux pratiques académiques** en traitement automatique du langage naturel (**NLP / TAL**) réalisés dans le cadre du Master 2 MIDS. L'objectif était de comprendre les fondements du traitement des textes, les représentations vectorielles, les méthodes d'apprentissage et le fonctionnement des modèles de langage, des approches classiques aux architectures Transformer.

Il s'agit d'un **portfolio de TP pédagogiques** et non d'un projet applicatif unique ni du développement d'un grand modèle de langage à partir de zéro.

## Contenu

| TP | Thématique | Notions mises en pratique | Notebook |
| --- | --- | --- | --- |
| **TP1** | Expressions régulières et loi de Zipf | Manipulation de textes, expressions régulières, fréquences lexicales et visualisations | [Regex et Zipf](TP1_Fondamentaux/regex_zipf.ipynb) |
| **TP2 — partie 1** | Représentations vectorielles | Couches d'embeddings avec PyTorch et opérations sur les tenseurs | [Embeddings](TP2_Modeles_Neuronaux/embeddings.ipynb) |
| **TP2 — partie 2** | Modèles de langage neuronaux | Architecture d'un modèle de langage, préparation de données textuelles et apprentissage avec PyTorch | [Modèle de langage neuronal](TP2_Modeles_Neuronaux/neural_language_model.ipynb) |
| **TP3** | Transformers | Tokenisation, représentation des séquences et mécanismes d'attention | [Tokenisation et attention](TP3_Transformers/tokenization_attention.ipynb) |
| **TP4** | Modèles préentraînés | Adaptation (*fine-tuning*) d'un modèle de langage préentraîné pour la classification de documents | [Classification de documents](TP4_Fine_Tuning/document_classification.ipynb) |
| **TP5** | Few-shot prompting | Expérimentation de prompts contenant des exemples pour orienter les prédictions | [Few-shot prompting](TP5_Prompting/few_shot_prompting.ipynb) |

## Objectifs pédagogiques

- Étudier les caractéristiques statistiques des corpus et les bases du prétraitement de textes.
- Comprendre la différence entre représentations creuses (*Bag-of-Words*) et représentations denses (*word embeddings*).
- Se familiariser avec l'implémentation de réseaux de neurones et de modèles de langage avec **PyTorch**.
- Étudier les mécanismes de **tokenisation**, d'**attention** et l'architecture **Transformer**.
- Explorer l'adaptation de modèles préentraînés (**fine-tuning**) et l'apprentissage en contexte (**few-shot prompting**).

## Environnement et technologies

- **Langage :** Python
- **Notebooks :** Jupyter Notebook / Google Colab
- **Deep Learning :** PyTorch
- **NLP :** Hugging Face Transformers, Datasets, NLTK
- **Analyse et visualisation :** NumPy, pandas, Matplotlib, scikit-learn
- **Accélération :** GPU Google Colab utilisé lors des séances et expérimentations qui le nécessitaient

Les notebooks proviennent de l'environnement de travail Google Colab. Certaines cellules peuvent nécessiter une connexion Internet, le téléchargement de jeux de données ou de modèles préentraînés, ou une configuration GPU adaptée.

## Exécuter les notebooks

1. Ouvrir le notebook souhaité directement depuis ce dépôt dans **Google Colab** (ou télécharger le fichier `.ipynb`).
2. Si nécessaire, activer un accélérateur dans **Exécution → Modifier le type d'exécution → GPU**.
3. Installer les dépendances : `pip install -r requirements.txt` ou exécuter les cellules d'installation présentes dans le notebook.
4. Exécuter les cellules dans l'ordre et tenir compte des ressources externes éventuellement nécessaires.

> Les résultats enregistrés dans les notebooks correspondent aux exécutions d'origine. Leur reproduction peut varier selon les versions des bibliothèques, les téléchargements externes et les ressources matérielles.

## Organisation du dépôt

```text
Natural-Language-Processing/
├── README.md
├── requirements.txt
├── TP1_Fondamentaux/
│   └── regex_zipf.ipynb
├── TP2_Modeles_Neuronaux/
│   ├── embeddings.ipynb
│   └── neural_language_model.ipynb
├── TP3_Transformers/
│   └── tokenization_attention.ipynb
├── TP4_Fine_Tuning/
│   └── document_classification.ipynb
└── TP5_Prompting/
    └── few_shot_prompting.ipynb
```

## Contexte et attribution

Ces expérimentations ont été menées **dans le cadre d'enseignements et de travaux pratiques universitaires**, à partir d'énoncés et de ressources pédagogiques. Le dépôt présente des notebooks de travail, et ne revendique pas la conception originale de toutes les architectures ni de l'intégralité des exercices fournis en cours.

Les **supports de cours** et les **corrigés de l'enseignante** ne sont pas publiés dans ce dépôt.

**Autrice du portfolio : Fatoumata NDOUR.**
