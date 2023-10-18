# Kaggle-Commonlit-NLP-2023

## Summary
The objective of this Kaggle competition was to develop a robust and accurate model for summary evaluation prediction. Our team achieved 68/2060 (Silver Medal) by harnessing the power of multiple BERT-based models and tree-based models in an Stacking + Bagging ensemble approach.

BERT-based models: 
* Roberta-base
* DeBERTa-base
* DeBERTa-large

Tree-based models:
* LightGBM
* XGBoost
* CatBoost

The ensemble methodology followed these key steps:

BERT-based Model Integration: We employed multiple pre-trained BERT-based models to extract meaningful representations from the text data. By combining the outputs of these models, we aimed to capture diverse linguistic nuances and improve the model's generalization capability.

Tree-based Models: After obtaining BERT-based embeddings and combining them with the engineered features, we fed the resulting feature set into various tree-based models (Stacking), including LightGBM, XGBoost, and CatBoost. To create the final predictions, we employed an bagging strategy that considered the outputs of different tree models. Weights of tree model outputs are automatically searched using Sequential Least SQuares Programming optimizer (SLSQP). 

## Feature Engineering

## Model Training

## Not Working Ideas

## References
