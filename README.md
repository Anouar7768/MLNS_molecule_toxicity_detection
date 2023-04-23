# MLNS_molecule_toxicity_detection
This repo contains the code of the project done as part of the MLNS course at CentraleSupelec.
Here is the details of what each file contains.

## Data folder
The Data folder contains the datasets used for training and testing along with the features extracted with the Graph2Vec and Mol2Vec methods.
- molecule_training.csv: labeled dataset of molecules, this dataset was split between training and testing datasets
- molecule_TestFeatures.csv: unlabeled dataset of molecules, this dataset was not used since it is not labeled
- graph2vec_embedding.csv and graph2vec_features.csv: features computed using the Graph2vec method
- mol2vec_features.csv: features computed using the Mol2vec methods

## Notebooks folder
The Notebook folder contains jupyter notebooks used for all the steps in our project (data exploration, feature extraction, feature engineering and classification, deep learning approach).
- 
