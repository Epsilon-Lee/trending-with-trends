
# :construction: Diffusion Model: past, present and future

Generative modeling in diffusion model is based on ***score-based modeling*** instead of other two popular modeling approaches **i)** likelihood modeling, e.g. autoregressive **ii)** implicit model, e.g. Generative Adversarial Network.

This (new)* direction astonishes me due to the following paper:

- [Diffusion Models Beat GANs on Image Synthesis](https://papers.nips.cc/paper/2021/file/49ad23d1ec9fa4bd8d77d02681df5cfa-Paper.pdf), `nips2021`
- [Guidance: a cheat code for diffusion models](https://benanne.github.io/2022/05/26/guidance.html), a blog post explaining the simple math formulation of diffusion model May 26 2022.

So this article aims at summarizing the following knowledge about diffusion models:

1. What is diffusion model mathematically?
  - [Generative Modeling by Estimating Gradients of the Data Distribution](https://yang-song.github.io/blog/2021/score/), May 5 2021.
  - [What are Diffusion Models?](https://lilianweng.github.io/lil-log/2021/07/11/diffusion-models.html), Jul. 11 2021.
3. What has it achieved in generative modeling, e.g. images, speeches, natural language?
4. Can it be used for modeling natural language, and its free/controllable generation?

> * might not be new, since every new trends in deep learning might be studied long ago without current great computation power.
