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
- Data_exploration.ipynb: notebook that contains the data exploration step as well as the representation of molecules using their graph or molecular representations
- Feature_extraction.ipynb: notebook that contains the code for the feature extraction step
- ML_models.ipynb: notebook that contains the code for the feature engineering (for example combination of different types of features) and the different tests made on the classical machine learning classifiers
- GNN_Molecule_Toxicity.ipynb: notebook that contains the code for the implementation of the deep-learning approach

## Additional file used
One file was used and could not be included in this notebook due to ist large size: it the file used to retrieve the pre-trained model for the mol2vec features. It can be retrieved from this link: https://github.com/samoturk/mol2vec/blob/master/examples/models/model_300dim.pkl
