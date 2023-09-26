# RS_team1_presentation1
Repository with materials related to the article DEEPLY UNCERTAIN: COMPARING METHODS OF UNCERTAINTY QUANTIFICATION IN DEEP LEARNING ALGORITHMS by @joaocaldeira and @bnord. The paper can be found at arXiv:2004.10710.

## Paper abstract 
"We present a comparison of methods for uncertainty quantification (UQ) in deep learning algorithms in the context of a simple physical system. Three of the most common uncertainty quantification methods - Bayesian Neural Networks (BNN), Concrete Dropout (CD), and Deep Ensembles (DE) - are compared to the standard analytic error propagation. We discuss this comparison in terms endemic to both machine learning ("epistemic" and "aleatoric") and the physical sciences ("statistical" and "systematic"). The comparisons are presented in terms of simulated experimental measurements of a single pendulum - a prototypical physical system for studying measurement and analysis techniques. Our results highlight some pitfalls that may occur when using these UQ methods. For example, when the variation of noise in the training set is small, all methods predicted the same relative uncertainty independently of the inputs. This issue is particularly hard to avoid in BNN. On the other hand, when the test set contains samples far from the training distribution, we found that no methods sufficiently increased the uncertainties associated to their predictions. This problem was particularly clear for CD. In light of these results, we make some recommendations for usage and interpretation of UQ methods."

## Replicating results
We replicated the code and obtained similar results. Run UQ_Analysis_notebook.ipynb to obtain our findings.


