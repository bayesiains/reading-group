# Bayesiains Reading Group

*Time and place*: 2–3:30pm on roughly alternate Mondays, IF 1.16.

## Rota

| Date  | Person | Paper(s) |
| --- | --- | --- |
| 20 Jan |  |  |
| 3 Feb |  |  |
| 17 Feb | Tiffany | [Partitioned integrators for thermodynamic parameterization of neural networks](https://arxiv.org/abs/1908.11843) |
| 9 Mar |  |  |
| 23 Mar |  |  |
| 6 Apr |  |  |
| 20 Apr |  |  |
| 4 May |  |  |
| 18 May |  |  |
| 1 June |  |  |
| 15 June |  |  |
| 29 June |  |  |


## Topics/papers

Reset the list for 2020. Brainstorm of ideas, not a schedule:

### Approximate Bayesian inference, calibration, ...

- ...


### Transfer learning, self-supervision, and friends

- ...


### Similarity and nearest neighbours

- [HNSW](https://arxiv.org/abs/1603.09320) for approximate nearest neighbours does well in some [benchmarks](http://ann-benchmarks.com/). (Although [FAISS](https://github.com/facebookresearch/faiss/wiki) offers [some discussion](https://github.com/facebookresearch/faiss/wiki/Guidelines-to-choose-an-index) of the choices for different regimes.)

- [nmslib](https://github.com/nmslib/nmslib) implements HNSW, and has a [reading list](https://github.com/nmslib/nmslib#related-publications).

- Any NN-graph methods? Classics like [isomap](http://www.sciencemag.org/cgi/content/abstract/290/5500/2319) and [LLE](http://www.sciencemag.org/cgi/content/full/290/5500/2323). Discuss how nearest neighbours can fit into more recent methods?


### Optimization

Anything that helps making practical choices, or gives insight into what choices matter?

Batch size:

- [Which Algorithmic Choices Matter at Which Batch Sizes? Insights From a Noisy Quadratic Model](http://papers.nips.cc/paper/9030-which-algorithmic-choices-matter-at-which-batch-sizes-insights-from-a-noisy-quadratic-model)

- [Measuring the Effects of Data Parallelism on Neural Network Training](https://arxiv.org/abs/1811.03600)

Learning rates:

- ...


### Discrete models

(Not continuous-like data, such as quantized images.)

Fast generation of high-dim patterns?

- [Non-Autoregressive Neural Machine Translation](https://arxiv.org/abs/1711.02281)
- [Latent-Variable Non-Autoregressive Neural Machine Translation with Deterministic Inference Using a Delta Posterior](https://arxiv.org/abs/1908.07181)
- RBMs?

Methods for latent variable models. Concrete distribution, REBAR/RELAX...?


### Unbiased estimation in learning

- More on [exact estimation with MCMC](https://sites.google.com/site/pierrejacob/articles)?

- [Unbiased scalable softmax optimization](https://arxiv.org/abs/1803.08577) (although [critical review](https://openreview.net/forum?id=H1bhRHeA-)

- [Efficient Optimization of Loops and Limits with Randomized Telescoping Sums](https://arxiv.org/abs/1905.07006)

- ...?


### Reinforcement learning?

- ...?


### Boosted trees

- A look at what's inside widely-used tools like [XGBoost](http://dmlc.cs.washington.edu/xgboost.html), [LightGBM](https://github.com/microsoft/LightGBM), or [CatBoost](https://catboost.ai/)?


