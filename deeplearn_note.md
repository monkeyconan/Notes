# Notes
reference: https://github.com/the-deep-learners/TensorFlow-LiveLessons

#### neurons
  * perceptron
  * sigmoid
  * tanh
  * ReLU
  

#### cost functions
  * quandratic (slow)
  * cross-entropy(perferred)
  
#### gradient descent
  * learning rate
  * mini-batch size
  * second-order (Adam)
  
#### initalization
After activation function the init values are still around 0.
  * Glorot uniform
  * Glorot normal 
  
#### regularization
  * L1/L2 reg
  * dropout
  * expand data
  
#### layers
  * dense
  * softmax
  * max-pooling
  * flatten
  * convolutional
  
  
## Word Embedding
target +  context     
If the window size = 2, each target word has 2+2=4 context words. For words at the beginning and the end of the sentence, "padding" is applied.

#### Word2vec architecture:
1. Skip-Gram: 
Produce the contect words given the target in the middle.      
Good for smaller dataset + rare words

2. CBOW, continuous bag of words: 
Produce target words given the context words. Sequence of the words is irrelavant. 
faster + frequent words

mini-batch size = 1(**CS224-N lecture 2**)

#### evaluteing word vectors
1. intrinsic
Perform on intermedia task, not on the final downstream NLP application

2. extrinsic
Perform on the downstream NLP application

#### word2vec Hyperparameters
1. n dimensions
2. windown size(good starting point SG~10, CBOW~5)
3. n iterations: more tend to be better but stop at some point
4. sample size
  
  
  
