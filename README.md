# dl
Filtering: light + correction (http://norvig.com/spell-correct.html) + spliting 
GloVe vocab + tweet = normalized(sum of all words/number of words)
SVC(default) for GloVe_wiki + lightFiltering = 0.7051, GloVe_wiki + HardFiltering = 0.7115, GloVe_twitter + lightFiltering = 0.7311, GloVe_twitter + HardFiltering = 0.7342

Without filtering + Glove_wiki = 0.6686

GloVe(http://nlp.stanford.edu/projects/glove/)

Tweet representation as a vector = normalized(sum of all words/number of words) doesn't make any sense. Accuracy less than after classifier.
