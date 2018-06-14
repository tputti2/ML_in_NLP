# Semantic Similarity

#### Objective

In this paper, we tackle the task of creating different models to classify semantic equivalence on question pairs. We utilize Quora’s 400,000 question pairs as released as part of a Kaggle competition. We utilize the Manhatten LSTM model that achieved state-of-the-art performance in this task, but also compare it against a universal sentence encoder that was recently released by Google. Our paper finds that Google’s sentence encoder was outperformed by a Siamese LSTM with Word2Vec embeddings.

