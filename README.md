# Hidden Markov Model  
Hidden Markov Model
SPIDAL Image Processing and Optimization Library  
A Hidden Markov Model is often used for sequential data, such as observations over time, the words of a sentence, etc, when connections are expected between the observations of the sequence (e.g., that variable values change relatively "smoothly" over time). 

Here we describe the theory behind HMMs, as well as some example applications. Often, values of some variables connected together by an HMM are known, while others are to be estimated. When one wants to estimate a distribution over an individual variable, i.e. Marginal Inference, use the [Forward-Backward Algorithm](https://github.com/hpcanalytics/Hidden-Markov-Model/tree/master/algorithm.forward-backward). When one wants to jointly estimate the most like value for all variables simultaneously, use the [Viterbi Algorithm](https://github.com/hpcanalytics/Hidden-Markov-Model/tree/master/algorithm.viterbi).  If one wants to estimate confidence intervals on variable values, or if the dimensionality of each variable is very high, a better choice might be approximate inference using [MCMC](https://github.com/hpcanalytics/Hidden-Markov-Model/tree/master/algorithm.mcmc).

