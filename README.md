# ID3 algorithm - Decision Tree

This algorithm uses entropy H(S) and Information gain IG(S) to decide the best attribute to split.The splits confrimed on highest Information gain or lowest entropy among all.

It is a recursive approach which find the entropy-information gain on the subsets and decide the split.

It measures acccuracy for both the train and test dataset.

The code for Id3 algorithms has following functions:
  - entropy (find the entropy with the bernouli distribution p)
  - infogain (calculate information gain for a particular splits)
  - find_maximum_infogain (it decides the feature with the highest information gain)
  - build_tree( it will build tree in a top-down manner,and selecting splits until hit a pure leaf or all splits look bad).


The dataset has already splitted in to test and train set and it has values in 0 & 1 for all attributes.
