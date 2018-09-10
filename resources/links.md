# Links to various papers and resources

## Link to our writeup

https://www.overleaf.com/12906574frzcjzngxfcq#/49351789/

## Early papers

1. Poincare embeddings: Poincaré Embeddings for Learning Hierarchical Representations, Nickel, Maximilian and Kiela, Douwe, NIPS 2017: https://arxiv.org/abs/1705.08039 

2. Neural Embeddings of Graphs in Hyperbolic Space, Benjamin Paul Chamberlain, James R Clough, Marc Peter Deisenroth: https://arxiv.org/pdf/1705.10359.pdf  

## More recent papers

1. Representation Tradeoffs for Hyperbolic Embeddings, Christopher De Sa, Albert Gu, Christopher Re, Frederic Sala, (Stanford and Cornell) : https://arxiv.org/pdf/1804.03329.pdf

2. Learning Continuous Hierarchies in the Lorentz Model of Hyperbolic Geometry M Nickel, D Kiela, ICML 2018: https://arxiv.org/abs/1806.03417  

## Word2Vec initial papers and popular blogposts

1. Initial word2vec papers: Distributed Representations of Words and Phrases and their Compositionality, Mikolov et. al., NIPS 2013: https://arxiv.org/pdf/1310.4546.pdf 

2. GloVE - one of the most popular word embeddings used in NLP (from Stanford NLP group): https://nlp.stanford.edu/projects/glove/

3. Sebastian Ruder's blogposts on word embeddings: (1) http://ruder.io/word-embeddings-1/ (2) http://ruder.io/word-embeddings-softmax/ (3) http://ruder.io/secret-word2vec/ (4) http://ruder.io/cross-lingual-embeddings/ (5) http://ruder.io/word-embeddings-2017/ (6) http://ruder.io/nlp-imagenet/

4. Chris Olah's blog posts on embeddings: (1) http://colah.github.io/posts/2014-03-NN-Manifolds-Topology/ (2) http://colah.github.io/posts/2014-07-NLP-RNNs-Representations/ 

5. ELMo, the newer crop of word embeddings: https://allennlp.org/elmo  

### Implementations and other resources

1. https://github.com/HazyResearch/hyperbolics -- implementation from the Stanford group (Chris Re). Also a blogpost: https://dawn.cs.stanford.edu/2018/03/19/hyperbolics/  

2. https://github.com/facebookresearch/poincare-embeddings -- implementation from the original authors of poincare embeddings from facebook ai research 

3. https://mnick.github.io/project/geometric-representation-learning/ -- homepage of M. Nickel about all his works in this area .. with pointers to code, talk and papers. also has an overview blogpost

4. https://mnick.github.io/publication/nickel2018learning/ -- M. Nickel's page about his ICL 2018 paper

5. https://nbviewer.jupyter.org/github/RaRe-Technologies/gensim/blob/poincare_model_keyedvectors/docs/notebooks/Poincare%20Report.ipynb ( Note: This is a 3rd party and a dated implementation. See above for the implementation from the original authors

6. Links to videos from Clay and his notes: Somewhat related to Dave's nice presentation today, Grant Sanderson (creator of the 3blue1brown on youtube channel videos: https://www.youtube.com/channel/UCYO_jab_esuFRV4b17AJtAw -- a favorite of mine) just happened to release another fantastic video, this time on quaternions, where he uses stereographic projection to develop the intuitions of quaternion operations.  
    https://www.youtube.com/watch?v=d4EgbgTm0Bg
... replete with his usual great animations.  As I follow things, everything done here involved using stereographic projections of "n-dimensional spherical spaces embedded in n+1 space" onto Euclidean space of R^n: a "2D sphere" (i.e., circle) onto R^1, a "3D sphere" (i.e., ball) onto R^2, and the a "4D sphere" onto R^3.  I'm not sure what it would mean to do stereographic projection from a "hyperbolic" space onto Euclidean space (possibly I misunderstood, but I think Dave counted stereographic projection of hyperbolic space as a "third" way to parameterize and work with hyperbolic spaces).  And, per our discussion, my understanding is that the stereographic projection isn't really the *one* of the three constructions we're currently more excited about.
