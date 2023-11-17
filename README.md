# NLP_Topic_modelling
Mono-lingual Text Analysis with Contextualized Topic Models Using Jeopardy Dataset

Here is the provided link for the google colab file: 
https://colab.research.google.com/drive/1dIfdBsz3OmsVqwI9T1a4smN6LiGww7I-?usp=sharing

Topic modeling analyzes documents to identify common themes and provide an adequate cluster. For example, a topic modeling algorithm could identify whether incoming documents are contracts, invoices, complaints, or more based on their contents.

Contextualized Topic Models are based on the Neural-ProdLDA variational autoencoding approach by Srivastava and Sutton (2017).
This approach trains an encoding neural network to map pre-trained contextualized word embeddings (e.g., BERT) to latent representations. Those latent representations are sampled variationally from a Gaussian distribution and passed to a decoder network that has to reconstruct the document bag-of-word representation.

In the above code we have used the jeopardy dataset that is available on kaggle, the have categorized based on unique show numbers, which led to the reduction of our data size from 27000 row values to 3623 values and then with the preprocessing with the question column. then we have used normal nlp preprocessing techuniques to first make it text data clean for preprocessing. We have reduced the dataset size (due to gpu constraints) by selecting random sample of 500 values.

Rest of the information is avilable in the code itself, and helped you understand this concept of topic modelling.
Cheers!
