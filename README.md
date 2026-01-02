# ai-fake-news-detection-xai
This repository presents an AI-driven fake news detection system developed using multiple supervised machine learning models across three diverse datasets. The project aims to accurately classify news content as real or fake while ensuring model transparency and interpretability through explainable AI techniques.

The entire workflow follows the Knowledge Discovery in Databases (KDD) framework, providing a structured and reproducible approach from raw data processing to model evaluation and interpretation.

# Datasets Used

The project utilizes three publicly available datasets, each contributing unique characteristics:

CIC Truth Seeker Dataset
Social media–based text dataset containing labeled tweets with metadata.
https://www.kaggle.com/datasets/sudishbasnet/truthseekertwitterdataset2023/data

MC_Fake Dataset
A multimodal dataset combining textual and structured features, suitable for mixed-feature learning.
https://github.com/qwerfdsaplking/MC-Fake

WELFake Dataset
A large-scale news dataset consisting of real and fake news articles and headlines.
https://data.europa.eu/data/datasets/oai-zenodo-org-4561253

# Methodology

Followed the KDD approach: Selection, Preprocessing, Transformation, Data Mining, and Evaluation
Applied TF-IDF vectorization for text representation
Trained and evaluated multiple machine learning classifiers
Used LIME and SHAP for model explainability and interpretability

# Explainable AI (XAI)

To enhance trust and transparency in predictions:
LIME was used for local, instance-level explanations
SHAP was used to analyze feature contributions using game-theoretic principles

reproducibility.
