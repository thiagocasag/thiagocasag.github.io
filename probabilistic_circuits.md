## A Study on Algorithms for Learning Probabilistic Circuit Structures

A recurring comment about neural networks is that, despite their high accuracy and success rates, their structure (and even their pre-selection of variables) leads to what is known as a "black-box" problem. This means, shortly, that after training such a model, its decision-making process is difficult to understand, and correcting potential training errors becomes challenging to track. As an alternative, one might consider using a generative model, which, once trained, retains an explicit probability distribution of the provided variables. A model that fits these conditions is known as a probabilistic circuit (or simply PC).

In the first stage of this project, the structure of this model was studied, and one of the techniques known in the literature for generating the "skeleton" of a probabilistic circuit based on a dataset was implemented.

In the second stage, an algorithm for finding modes of a PC was studied. As mentioned earlier, being a generative model, it represents a probability distribution. For certain tasks, it is useful to find the peaks of these distributions, known as modes, which usually represent the most probable states. This algorithm was implemented, and some characteristics of the technique were verified on artificially generated datasets, such as convergence area in the domain and algorithm convergence speed.

All the work produced was implemented in the _Julia_ language and can be accessed [here](https://github.com/thiagocasag/ic-tcc).
