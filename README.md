# Residual Stack LSTM with Biased Decoding
  

The implementation differs from the original paper in these ways:
  1) no lexicons
  2) Nadam optimizer used instead of SGD
  3) Parameters: LSTM cell size of 200 (vs 275), dropout of 0.5 (vs 0.68)



# Result 
  The implementation achieves a test F1 score of ~86 with 30 epochs. Increase the number of epochs to 80 reach an F1 over 90. The score produced in Chiu and Nichols (2016) is 91.62. 

# Dataset
  Indian Culinary Dataset GloVe vector representation from Jeffrey Pennington, Richard Socher, and Christopher D. Manning. 2014. See https://nlp.stanford.edu/projects/glove/

# Dependencies 
    1) numpy 
    2) Keras
    3) Tensorflow
    4) Stanford GloVE embeddings
 
 
 
 
 
