**Update:** Blog posts: [DDPMs from scratch](https://magic-with-latents.github.io/latent/ddpms-series.html)

# Diffusion Models

Diffusion models are a class of likelihood-based generative models that recently have been used
to produce very high quality images compared to other existing generative models like GANs.
For example, take a look at the latest research [Imagen](https://imagen.research.google/) or
[GLIDE](https://arxiv.org/abs/2112.10741)where the authors used diffusion models to generate
very high quality images.

Although you can find a lot of material online regarding other generative models like GANs to
learn from, the list of resources for learning about diffusion models is still sparse. On top
of it, the mathematics behind the diffusion models is a bit harder to understand. To address
this, we are creating this repo to give you enough material to make you understand the
working of diffusion models and the maths involved.

We try to keep everything organized in notebooks which you can run on **Colab.**
We are also organizing the content in a series of short blog-posts but that would take some time.
Also, some of the notebooks presented here are marked as *optional*. These notebooks covers
the theoretical parts that you should be aware of before reading about diffusion models. 

---

## Table of Contents

| Chapter No   | <div style="width:250px">Topic</div> | Colab | GitHub |
| ------------ | -----------------------------------  | ----- | ------ |
|  1.  |[**Random Variables (Optional)**](https://magic-with-latents.github.io/latent/posts/ddpms/part1/)| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AakashKumarNain/diffusion_models/blob/main/notebooks/Random%20Variables.ipynb) |[![Open in GitHub](https://img.shields.io/static/v1?label=&message=Open%20in%20GitHub&labelColor=grey&color=blue&logo=github)](https://github.com/AakashKumarNain/diffusion_models/blob/main/notebooks/Random%20Variables.ipynb) |
|  2.  | [**Gaussian Distribution and DDPMs**](https://magic-with-latents.github.io/latent/posts/ddpms/part2/)| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AakashKumarNain/diffusion_models/blob/main/notebooks/all_you_need_to_know_about_gaussian.ipynb) |[![Open in GitHub](https://img.shields.io/static/v1?label=&message=Open%20in%20GitHub&labelColor=grey&color=blue&logo=github)](https://github.com/AakashKumarNain/diffusion_models/blob/main/notebooks/all_you_need_to_know_about_gaussian.ipynb) |
|  3.  | [**A deep dive into DDPMs**](https://magic-with-latents.github.io/latent/posts/ddpms/part3/)| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AakashKumarNain/diffusion_models/blob/main/notebooks/deep_dive_into_ddpms.ipynb) |[![Open in GitHub](https://img.shields.io/static/v1?label=&message=Open%20in%20GitHub&labelColor=grey&color=blue&logo=github)](https://github.com/AakashKumarNain/diffusion_models/blob/main/notebooks/deep_dive_into_ddpms.ipynb) |
