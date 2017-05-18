# relational-classification
Implements a log-linear classification model based  on relational features from Bayesian network learning. Under Construction.

Input: 

1. A relational database
2. A target instance (e.g. genre(BraveHeart) in IMDB)
3. A learned Bayesian network (using [FactorBase](https://github.com/sfu-cl-lab/FactorBase).

Output: A probability distribution over values of the target instance. 

Implements our relational dependency network formula from the paper [
Fast Learning of Relational Dependency Networks] (http://www.cs.sfu.ca/~oschulte/pubs.html). 

