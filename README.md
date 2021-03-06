# Hidden Markov Models

A Hidden Markov Model is often used for sequential data: the words of a sentence, the sentences of a document, the phonemes of speech, financial market prices over time, etc. They are typically used when one wants to estimate the value of a variable over time, given  imperfect observations. 

Here we describe the theory behind HMMs, as well as some sample applications. Often, values of some variables connected together by an HMM are known, while others are to be estimated.  There are  three different algorithms available for performing different types of inference on HMMs:

* The [Forward-Backward Algorithm](https://github.com/hpcanalytics/Hidden-Markov-Model/tree/master/algorithm.forward-backward): When one wants to estimate a distribution over an individual variable, i.e. Marginal Inference. 
* The [Viterbi Algorithm](https://github.com/hpcanalytics/Hidden-Markov-Model/tree/master/algorithm.viterbi): When one wants to jointly estimate the most likely value for all variables simultaneously, i.e. Maximum A Posterior (MAP) inference.  
* The [Markov Chain Monte Carlo (MCMC) Algorithm](https://github.com/hpcanalytics/Hidden-Markov-Model/tree/master/algorithm.mcmc): When one wants to estimate confidence intervals on variable values, or if the dimensionality of each variable is very high, the approximation algorithm be best.

## Theory behind HMMs

### Background: Markov Chains
<a href="http://www.youtube.com/watch?feature=player_embedded&v=kpz28cggDy8
" target="_blank"><img src="https://github.com/hpcanalytics/Hidden-Markov-Model/blob/master/resource/Background-Markov%20Chains.png" 
width="340" height="200" border="10" /></a>

### Markov Chain Examples
<a href="http://www.youtube.com/watch?feature=player_embedded&v=IIXR1-iDHNU
" target="_blank"><img src="https://github.com/hpcanalytics/Hidden-Markov-Model/blob/master/resource/Markov%20Chain%20Examples.png" 
width="340" height="200" border="10" /></a>

### Hidden Markov Models
<a href="http://www.youtube.com/watch?feature=player_embedded&v=oGqp_fAv5S8
" target="_blank"><img src="https://github.com/hpcanalytics/Hidden-Markov-Model/blob/master/resource/Hidden%20Markov%20Models.png" 
width="340" height="200" border="10" /></a>



## Examples

### Turbo codes, Natural Language Processing
<a href="http://www.youtube.com/watch?feature=player_embedded&v=WSrIjkOtg7g" target="_blank"><img src="https://github.com/hpcanalytics/Hidden-Markov-Model/blob/master/resource/Turbo%20codes%2C%20Natural%20Language%20Processing.png" 
width="340" height="200" border="10" /></a>


### Part-of-speech tagging, Temporal popularity modeling
<a href="http://www.youtube.com/watch?feature=player_embedded&v=qeVbSsx67ps" target="_blank"><img src="https://github.com/hpcanalytics/Hidden-Markov-Model/blob/master/resource/Part-of-speech%20tagging%2C%20Temporal%20popularity%20modeling9.png" 
width="340" height="200" border="10" /></a>


### Scene recognition
<a href="http://www.youtube.com/watch?feature=player_embedded&v=u-8J2uEMeyM" target="_blank"><img src="https://github.com/hpcanalytics/Hidden-Markov-Model/blob/master/resource/Scene%20recognition.png" 
width="340" height="200" border="10" /></a>












