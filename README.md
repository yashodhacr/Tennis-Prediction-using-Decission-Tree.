# Tennis-Prediction-using-Decission-Tree.
-------
The objective here is to choose the days which are suitable to play Tennis based on the weather given.

Decision Trees concept has been used here to classify the days which are suitable and not suitable to play Tennis since it is very different from other classification models available in Machine learning domain.

## Decision Trees
-------
Basically, Decision Trees uses "if", "else" like conditions, which are very easy to interpret.

Decision Trees divides the space into set of axis parallel hyperplanes that breaks the space into hypercubes, hypercuboids.
Most importanat terms for building Dicision Tree inlcudes, 1) Entropy
                                                           2) Information Gain
                                                           3) Gini Impurity

The data set includes four feature 1) Outlook 2) Temperature 3) Humidity 4) Wind

Calculated the Entropy of the dataset. Inorder to choose the rootnode out of four features available, Information gain has been performed on them. After performing information gain calcualtion, the one with the high information gain has to be selected as a root node. 

"Outlook" will be selected as a rootnode Since it has got the high Information gain.

Again Outlook has three subnodes 1)Sunny 2) Overcast 3)Rain and days will be classified accordingly.


