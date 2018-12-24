# Named-Entity-Recognition-BLSTM-CNN-CoNLL
  Keras implementation of the Bidirectional LSTM and CNN model similar to Chiu and Nichols (2016) for CoNLL 2003 news data. Paper: https://arxiv.org/abs/1811.05468

# The difference from the original code:
    1) Layer Position(The Embedding vectors are inputed to BLSTM before be concatenated)
    2) Duplicate BLSTM Layer 

This code is from https://github.com/mxhofer/Named-Entity-Recognition-BidirectionalLSTM-CNN-CoNLL

# Result 
   The implementation achieves a test F1 score of 82.86 with 10 epochs.
   Increase the number of epochs to 80 reach an F1 over 90.

# Dataset
  CoNLL-2003 newswire articles: https://www.clips.uantwerpen.be/conll2003/ner/
  GloVe vector representation from Jeffrey Pennington, Richard Socher, and Christopher D. Manning. 2014.
  See https://nlp.stanford.edu/projects/glove/

# Dependencies 
    1) numpy 1.15.4
    2) Keras 2.1.6
    3) Tensorflow 1.8.0
    4) Stanford GloVE embeddings
    need to install pydot, graphviz(pip install doesn't work, do make install)
 
 
 
 
 
