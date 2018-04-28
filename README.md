# Deep Learning Models for Text Classification

This repo provide Jupyter notebook for deep-learning models employed in sentiment-analysis type of NLP problem. 
The notebook is based on the dataset provided in a recent Kaggle competition 'Toxic Comment Classification Challenge' sponsered by Google.

I found the competition and dataset unique for an accesible and beginner-friendly introduction to practical deep-learning for NLP. The notebook introduces a number of NLP and deep-learning techniques such as word-embeddings, pre-trained word vectors, recurrent neural nets, combining RNN with CNN, and even some Keras on the way.

# How to run experiments?

1. Create a 'data' folder and put train, test, and sample submission files from Kaggle.
2. Create a 'vector' folder and put glove840B word vector.
3. If running on CPU-only machine, you need to change CuDNNGRU to GRU.
4. I have put most of the important model parameters in separate cells so that you can finetune them.

# Requirements:

1. Keras with Tensorflow backend
2. Python 3.5 (recommended to install using Anaconda)



