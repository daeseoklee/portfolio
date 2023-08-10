# portfolio

My research works are classified here into three categories, and each of them corresponds to a directory. For each category, I listed the items in the chronological order while briefly explaining them.

### Published works
* On the Complexity of Finite Sequences over Finite Sets, with Soonja Kang, 2014 (./published/string_complexity.pdf)

This is based on my final project in *CNU Science Education Institute for the Gifted* when I was in middle school. 

It came out of a naive question like "How can we quantify degree to which a sequence of characters is repetitive?". We gave a possible definition and analyzed some simple statistics around it. In particular, based on a lower bound that is easier to manipulate, we showed the average value of it is linear in the length of the sequence when the number of distinct characters is >= 3.

* Different Volume Computational Methods of Graph Polytopes, with Hyeong-Kwan Ju and Sangwook Kim, 2018 (./published/graph_polytope_volume.pdf)

It is about an elementary enumerative combinatorial problem raised by H.K. Ju, which is to calculate(the main term of) the number of vectors x in [N]^n which satisfies certain linear contraints of the form x_i+x_j<=N (ij is an edge of a given graph on n vertices). 

We developed many elementary methods, among which there was an unexpected simple recursive formula that provides a general algorithm. 


* Altering LCA of dependency parse trees for improving relation
extraction from adjective clauses, with Sung-Hyon Myaeng, 2018 (./published/dependency_parsing_LCA.pdf)

Dependency parsing is a method of generating a syntactic structure that represents the dependency relations of entities in a sentence. It can serve as an intermediate feature that can be used in many tasks in NLP, including *relation extraction*. 

We identified a tiny fragment in the grammar of dependency parsing that can be possibly mis-aligned with (the justification of) some particular ways that the parse tree is used in *relation extraction*, and suggested to take that case separately and perform a tiny surgery(of the tree) before applying the methods. 

### Unpublished works

* Faster Calculation of String Subsequence kernel, 2018 (./unpublished/faster_ssk.pdf)

Just as the title suggests. The algorithm was found while doing the 'dependency parsing' project.  

* Boosting Convolutional Neural Networks' Protein Binding Site Prediction Capacity Using SE(3)-invariant transformers, Transfer Learning and Homology-based Augmentation 

https://arxiv.org/abs/2303.08818

* Improving group robustness under noisy labels using predictive uncertainty 

https://arxiv.org/abs/2212.07026

### Incomplete works
* Assessing Generalizability of Maximum Likelihood Estimation, 2020 (./incomplete/mle_bounds.pdf)

Some preliminary ideas on extending the classical learning theory(using Radamacher complexity) to the setting of distribution learning. 

For a quick overview, you can read section 1 and 2 for the problem description and notations, read the statement of Theorem 5.2, and jump to section 7. In section 7, focus on the initial remarks, Theorem 7.8 and subsection 7.3. 

* Inference in Functional Probabilistic Models, 2020 (./incomplete/iifpm.pdf)

Tried to provide a framework to analyze the problem of approximating the conditional distribution when the dimension of the space in which the latent variables lie decreases by conditioning.(Such conditional distribution can be viewed as 'disintegration'.)

In particular in Theorem 3.6, we proved in a setting that making certain quantities(equations (3.10) and (3.11), which have trivial Monte-Carlo estimations) near-zero is sufficient for the approximation in a special sense(equation (3.9) and the following line). Read the lines around equation (3.25).  


