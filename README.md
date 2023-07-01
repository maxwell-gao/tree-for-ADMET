# tree-for-ADMET
Use a tree-based model to interpret the AMDET properties of small molecules based on large-scale CPI(compound-protein interaction) sequences.
## Main Hypothesis
AMDET stands for absorption, metabolism, distribution, excretion, and toxicity, and it is an essential aspect of drug discovery and development, here, we assume that these properties are not specific to a particular protein but rather related to a series of proteins interacting with each other. Therefore, by using CPI sequences, we can capture the global and contextual information of compound-protein interactions, which may be relevant for AMDET prediction.
## CPI sequences
CPI sequences refer to sequences of compound-protein interactions that represent the binding affinity of a compound to a set of proteins. By scoring the binding of predicted compounds with individual proteins and combining these scores to create a large-scale CPI sequence, we can train a tree-based model to learn the patterns and features associated with different AMDET properties.
## Tree-based model
A tree-based model is a type of machine learning algorithm that can handle complex and nonlinear data, and can also provide interpretable results by showing the importance of different features and the decision rules for each prediction. To predict AMDET properties from CPI sequences, the tree-based model takes a CPI sequence as an input and passes it through each decision tree in the collection.
