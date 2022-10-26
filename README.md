# Pain, I can't see the panorama tag! There is no this tag...
How often do you read the news lately and don't see the panorama tag, although it should be... 
It becomes a big problem for me... 
Fortunately I am learning data science and I have all tools for split news to classes.

In first part of my project I have uploaded 4k posts from ia_panorama and 4k from rt_russia.
1. Prepeared data (clean from data leak and etc.) in 'make_data.ipynb' 
2. Make neural network based on bert layer, pretrained on russian texts 'NN.ipynb'
Due to a lack of computational power, I trained the neural network only for 10 epochs.
3. Extract features and test our base model on test data 'make_features.ipynb'
4. Improve this using XGBoost and meta features 'xgb.ipunb'

The second part is - clustering comments from lentach.
1. Clean comments in 'clean_comments.ipynb'
2. Clustering it using tf-idf 'cluster_tfidf.ipynb'
3. Clusterint it using features from NN 'cluster_NN.ipynb'
