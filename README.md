# Bayesiains Reading Group

*Time and place*: 9.30am on Wednesdays until 28 August 2019, IF 1.16

From Monday 2 September 2019, we'll be at 2pm on Mondays, IF 1.16.

## Rota

| Date  | Person | Paper(s) |
| --- | --- | --- |
| 9 Jan | George | [Neural Ordinary Differential Equations](https://arxiv.org/abs/1806.07366)<br/>[FJORD: Free-form Continuous Dynamics for Scalable Reversible Generative Models](https://arxiv.org/abs/1810.01367) |
| 16 Jan | Artur | [Do Deep Generative Models Know What They Don't Know?](https://arxiv.org/abs/1810.09136) |
| 23 Jan | James | [Getting It Right: Joint Distribution Tests of Posterior Simulators](https://www.jstor.org/stable/27590449) |
| 30 Jan | Conor | [Decomposition of Uncertainty in Bayesian Deep Learning for Efficient and Risk-sensitive Learning](https://arxiv.org/abs/1710.07283) |
| 6 Feb | Asa | [Attention Is All You Need](https://arxiv.org/abs/1706.03762) <br/> [The Annotated Transformer](http://nlp.seas.harvard.edu/2018/04/03/attention.html) |
| 13 Feb | Iain | [Extreme Components Analysis](https://papers.nips.cc/paper/2517-extreme-components-analysis) <br/> [Bayesian Extreme Components Analysis](https://www.ics.uci.edu/~welling/publications/papers/BayesianXCA_IJCAI09%28color%29.pdf) |
| 20 Feb | George | [Sylvester Normalizing Flows for Variational Inference](https://arxiv.org/abs/1803.05649) <br/> [Improving Variational Auto-Encoders using Householder Flow](https://arxiv.org/abs/1611.09630) <br/> [Emerging Convolutions for Generative Normalizing Flows](https://arxiv.org/abs/1901.11137) |
| 27 Feb | Artur | [Invertible Residual Networks](https://arxiv.org/abs/1811.00995) |
| 13 Mar | James | [Particle MCMC](http://dx.doi.org/10.1111/j.1467-9868.2009.00736.x) and Darren Wilkinson's [blog posts](https://darrenjw.wordpress.com/2014/01/25/introduction-to-the-particle-gibbs-sampler/) |
| 20 Mar | Conor | Causality. Background reading: Ference blog posts ([1](https://www.inference.vc/untitled/), [2](https://www.inference.vc/causal-inference-2-illustrating-interventions-in-a-toy-example/), [3](https://www.inference.vc/causal-inference-3-counterfactuals/)) and reminder of DAG basics ([pmr notes](https://www.inf.ed.ac.uk/teaching/courses/pmr/18-19/assets/slides/slides03b.pdf)) |
| 27 Mar | Iain | [Self-tuning neural networks](https://arxiv.org/abs/1903.03088) ([openreview discussion](https://openreview.net/forum?id=r1eEG20qKQ)) |
| 10 Apr | Asa | [Quasi-Recurrent Neural Networks](https://arxiv.org/abs/1611.01576) ([use-case for mobile devices](https://ai.googleblog.com/2019/03/rnn-based-handwriting-recognition-in.html))
| 17 Apr | Artur | [Hybrid Models with Deep and Invertible Features](https://arxiv.org/abs/1902.02767) |
| 8 May  | James | [Validating Bayesian Inference Algorithms with Simulation-Based Calibration](https://arxiv.org/abs/1804.06788) |
| 15 May  | Conor | Maximum Mean Discrepancy with a dash of functional analysis. [A Kernel Method for the Two-Sample Problem](https://papers.nips.cc/paper/3110-a-kernel-method-for-the-two-sample-problem), [A Kernel Two-Sample Test](http://jmlr.csail.mit.edu/papers/v13/gretton12a.html), [Generative Moment Matching Networks](https://arxiv.org/abs/1502.02761), [StackExchange post](https://stats.stackexchange.com/a/276618), [inevitable Ferenc blog post](https://www.inference.vc/another-favourite-machine-learning-paper-adversarial-networks-vs-kernel-scoring-rules/). |
| 26 June | Iain  | Information Theory basics 1/2, information, entropy and source coding. Readings from [David MacKay's book](http://www.inference.org.uk/itila/book.html). Chapter 4 starts with accessible intuition for information content and entropy (then gets harder going as moves towards proving the source coding theorem). Chapters 5 and 6 talk about how to actually compress data down to its entropy, read at least up to Section 5.4 for the connection to KL-divergence. Summary of key definitions on p32–35. |
| 3 July | Iain  | Information Theory basics 2/2, noisy channel coding. Readings from [David MacKay's book](http://www.inference.org.uk/itila/book.html). A really high-level overview is the introduction in chapter 1 (skimming over details of Hamming codes), and then Chapter 9 gives an intuitive overview. (The proof itself is in Chapter 10.) Summary of key definitions p138–139. |
| 10 July | | _No meeting._ |
| 17 July | Asa | [Sparse Gaussian Processes](https://papers.nips.cc/paper/2857-sparse-gaussian-processes-using-pseudo-inputs). [Useful blog post](https://www.prowler.io/blog/sparse-gps-approximate-the-posterior-not-the-model)|
| 24 July | Artur | Intro to neural processes. </br> [Conditional Neural Processes](https://arxiv.org/abs/1807.01613). </br> [Neural Processes](https://arxiv.org/abs/1807.01622). </br> [Neural Processes as distributions over functions (blog post)](https://kasparmartens.rbind.io/post/np/)
| 31 July | Conor | [Stacked Capsule Autoencoders](https://arxiv.org/abs/1906.06818) and associated [blog post](http://akosiorek.github.io/ml/2019/06/23/stacked_capsule_autoencoders.html)
| 7 August | | _No meeting._ |

## Topics/papers

### Variational Inference

- [x] [Blei's VI tutorial](https://arxiv.org/abs/1601.00670)
- [Local Reparameterization Trick](https://arxiv.org/abs/1506.02557). Excl. variational dropout stuff. More detailed treatment in related [PhD thesis (PDF)](https://www.dropbox.com/s/v6ua3d9yt44vgb3/cover_and_thesis.pdf?raw=1).
- [Multiplicative Normalizing Flows for Variational Bayesian Neural Networks](https://arxiv.org/abs/1703.01961)
- K-FAC:
  - [Optimizing Neural Networks with Kronecker-factored Approximate Curvature](https://arxiv.org/abs/1503.05671)
  - [x] [Noisy Natural Gradient as Variational Inference](https://arxiv.org/abs/1712.02390)
- [Fast and Scalable Bayesian Deep Learning by Weight-Perturbation in Adam](https://arxiv.org/abs/1806.04854)
- [
The Description Length of Deep Learning Models](https://arxiv.org/abs/1802.07044). Information theoretic analysis of variational approximations for neural nets.
  
### Sampling methods

- [x] [Sequential Monte Carlo (PDF)](https://www.stats.ox.ac.uk/~doucet/doucet_defreitas_gordon_smcbookintro.pdf)
- [Particle Gibbs sampling (PDF)](https://www.stats.ox.ac.uk/~doucet/andrieu_doucet_holenstein_PMCMC.pdf)
- [x] [Annealed Importance Sampling](https://arxiv.org/abs/physics/9803008)

### EP/ADF

- [x] [Expectation Propagation for approximate Bayesian inference](https://arxiv.org/abs/1301.2294). Also related [PhD thesis (PDF)](https://tminka.github.io/papers/ep/minka-thesis.pdf)
- For NNs:
  - [Probabilistic Backpropagation for Scalable Learning of Bayesian Neural Networks](https://arxiv.org/abs/1502.05336)
  - [Expectation Propagation for Neural Networks with Sparsity-promoting Priors](https://arxiv.org/abs/1303.6938)
  
### Classic papers

- [A Unifying Review of Linear Gaussian Models (PDF)](http://mlg.eng.cam.ac.uk/zoubin/papers/lds.pdf)
