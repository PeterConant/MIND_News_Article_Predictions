# MIND_News_Article Predictions
### Authored by: Peter Conant, Kareema Kilani, Monish Lakmraju

## DataSet
The MIND Dataset is collected from anonymized behavior logs of the Microsoft News Website as a large scale data set for new recommendation research. It contains interactions called impressions from 1 million users and contains data points for 160k English New articles. The main dataset is too large for the scope of this project, therefore we use the MIND-small dataset containing 50,000 users and their behavior. In this paper we refer to the MIND-small dataset as MIND for simplicity as the larger MIND dataset was not used at all.

## Task distribution

#### Peter Conant
Created a graph representation of the data and trained the TransE for Knowledge Graph Embedding predictions
* KG_Embeddings.ipynb
* MIND_Graph_Visualization.ipynb
* node2vec_embedding.ipynb


#### Kareema
Identified appropriate evaluation methods and create base (none machine learning) model 
* Conent_based_recommender_system_*

#### Monish
Extracted Extra features using sentiment analysis on abstracts/titles and created and evaluated the Two Tower Model
* TwoTower_Recommender_TextOnly.ipynb
* TwoTower_Recommender_with_Sentiment.ipynb
