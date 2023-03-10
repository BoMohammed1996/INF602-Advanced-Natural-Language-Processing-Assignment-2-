# INF602-Advanced-Natural-Language-Processing-Assignment-2-
Finding the quantitative correlations over narratives written in natural language is essential for solving Math Word Problems (MWPs). Recent studies have shown that current robustness models depend on superficial heuristics and contextual memorization to solve MWPs. In this study, we investigate this problem and propose that it results from a general misunderstanding of MWP patterns. 
First, we look at the neural network's semantic understanding of patterns and find that, if the prototype equations are the same, such n1 + n2, most issues acquire closer representations while representations far from them or near to other prototypes likely to provide erroneous answers. Based on this, we suggest a contrastive learning strategy in which the neural network looks for differences between patterns. 
In order to gather contrasting instances, we first transform the prototype equation into a tree and then look for other equations with a tree structure. 
The gathered instances are used to train the solution robustness model with an additional aim, which brings together the models of issues with comparable prototypes. 
As a part of our investigations, we use both the Math23k dataset and the MathQA dataset. 
Monolingual and multilingual environments both benefit considerably from our method's performance enhancements.
