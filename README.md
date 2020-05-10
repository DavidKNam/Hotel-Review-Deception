# Hotel-Review-Deception

**Motivation / Problem Statement:**

With e-commerce transforming the way in which individuals and businesses conduct trades, online reviews have become a great source of information among consumers. With 93\% of shoppers relying on online reviews to make their purchasing decisions, the credibility of reviews should be strongly considered. While detecting deceptive text has proven to be a challenge for humans to detect, it has been shown that machines can be better at distinguishing what is truthful and deceptive online by applying pattern analysis on a large amount of data. This study looks at the use of several popular pre-trained word embeddings (Word2Vec, GloVe, fastText) that are available online, with deep neural network models (CNN, BiLSTM, CNN-BiLSTM) to determine the influence of word embedding on the accuracy of detecting deception. Some pre-trained word embeddings have shown to adversely affect the classification accuracy when compared to training the model on text embedding using the domain specific data. Through the combination of CNN and BiLSTM without any pre-trained word embeddings, an accuracy of 89.2 percent was achieved on the hotel review dataset published by Ott et al. in 2011. 


**Main Objective:** Implement different Deep Neural Network Models to Detect Deception within Hotel Review. Utilize popular pre-trained word embeddings to compare their effect and performance on the models.

**Task 1:** Download the Hotel Review Dataset (Ott et al.) and preprocess it.

**Task 2:** Build Models to test their performance on the dataset.

**Task 3:** Incorporate different pre-trained word embeddings to the models.
