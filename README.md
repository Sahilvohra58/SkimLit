# SkimLit

The SkimLit project aims to do text classification of text for parts of abstracts of research papers.

The project aimn on building machine learning and deep learning models that can produce comparable results to [PubMed 200k RCT: a Dataset for Sequential Sentence Classification in Medical Abstracts](https://arxiv.org/abs/1710.06071) 


The dataset consists of around 200,000 example of abstracts collected from different research papers. 

Every abstract recorsd has sentences that belong to either of these categories:

1. OBJECTIVE
2. METHODS
3. RESULTS
4. CONCLUSIONS
5. BACKGROUND

The project aims to classify each sentence into either of these sentences.


The project follows the these experimental steps:

1. Model 0: Naive Bayes - Tfidf Multinomial.
2. Model 1: Small deep learning model with work tokenization and embedding.
3. Model 2: Using pretrained embedding (transfer learning).
4. Model 3: Deep learning with character tokenization and embedding.
4. Model 4: Deep learning with word (transfer learning) and character tokenization and embedding.
5. Model 5: Deep learning with word (transfer learning), character and positional embedding.

