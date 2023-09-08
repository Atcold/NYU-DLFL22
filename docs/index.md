---
layout: default
title: DEEP LEARNING
author: Alfredo Canziani
lang-ref: home
---

**DS-GA 1008 · FALL 2022 · [NYU CENTER FOR DATA SCIENCE](http://cds.nyu.edu/)**

| INSTRUCTOR  | Alfredo Canziani, Yann LeCun                                     |
| LECTURES    | Wednesday 16:55 – 18:55, Zoom                                    |
| PRACTICA    | Tuesdays 16:55 – 17:55, Zoom                                     |
| FORUM       | [r/NYU_DeepLearning](https://www.reddit.com/r/NYU_DeepLearning/) |
| DISCORD     | [NYU DL](https://discord.gg/CthuqsX8Pb)                          |
| MATERIAL    | [2022 repo](https://github.com/Atcold/NYU-DLFL22)                |


## 2022 edition disclaimer

Check the repo's [`README.md`](https://github.com/Atcold/NYU-DLFL22/blob/master/README.md) and learn about:

- New content and presentation
- This semester repository
- Previous releases


## Lectures

Only the new lessons (either material or presentation) will come online.
<span class="missing">Context similar to the [SP21 edition](../NYU-DLSP21/), semitransparent and shown in italic, is not going to be edited and/or pushed online.</span>

**Legend**: 🖥 slides, 📝 notes, 📓 Jupyter notebook, 🎥 YouTube video.

<style>
.missing {
    opacity: 0.4;
    font-style: italic;
}
hr {
    opacity: 0.4;
    margin-top: 2.5em;
}
</style>

### Theme 1: Introduction

- 00 – Introduction to NYU-DLFL22 [🎥](https://youtu.be/00s9ireCnCw)
- <span class="missing"> 01 – History (see [🎥](https://youtu.be/mTtDfKgLm54)) </span>
- <span class="missing"> 02 – Gradient descent and the backpropagation algorithm (see [🎥](https://youtu.be/nTlCqaL7fCY)) </span>
- 03 – Resources and neural nets inference [🎥](https://youtu.be/QwZQrxIk6Dg)


### Theme 2: Classification, an energy perspective

- 05 – Notation and introduction [🎥](https://youtu.be/9cpBu8yt9B8) [🖥](https://drive.google.com/file/d/1c0aElks9f9A2PWRNDJO1P_5_n9ODA--o/)
- 06 – Backprop and contrastive learning [🎥](https://youtu.be/SC6ljsFFVcY) [🖥](https://drive.google.com/file/d/1c0aElks9f9A2PWRNDJO1P_5_n9ODA--o/)
- 07 – PyTorch 5-step training code [🎥](https://youtu.be/PXXE7aJ_siw) [🖥](https://drive.google.com/file/d/1c0aElks9f9A2PWRNDJO1P_5_n9ODA--o/)


### Theme 3: Parameter sharing

- <span class="missing"> 04 – Recurrent and convolutional nets (see [🎥](https://youtu.be/7dU3TFBJl-0) [🖥](https://drive.google.com/file/d/1GtI4ywzI84oamyr_W5k_wzgfRN139aFD/) [📝 ](https://drive.google.com/file/d/12jP4ssUIoGURAU8jGj6QwKXyZVdXW0o6/)) </span>
- <span class="missing"> 08 – Natural signals, ConvNets kernels and sizes, comparison with fully-connected architecture (see [🎥](https://youtu.be/KvvNkE2vQVk) [🖥](https://github.com/Atcold/NYU-DLSP20/blob/master/slides/02%20-%20CNN.pdf) [📓](https://github.com/Atcold/NYU-DLSP20/blob/master/06-convnet.ipynb) and [🎥](https://youtu.be/d2GixptaHjk?t=2211)) </span>
- <span class="missing"> 09 – Recurrent neural nets, vanilla and gated (LSTM) [🎥](https://youtu.be/5KSGNomPJTE) [🖥](https://github.com/Atcold/NYU-DLSP20/blob/master/slides/04%20-%20RNN.pdf) [📓](https://github.com/Atcold/NYU-DLSP20/blob/master/08-seq_classification.ipynb)[📓](https://github.com/Atcold/NYU-DLSP20/blob/master/09-echo_data.ipynb) ① </span>


### Theme 4: Energy-based models, a compendium

- <span class="missing"> 11 – Inference for latent variable energy-based models (LV-EBMs) [🎥](https://youtu.be/xA_OPjRby5g) [🖥](https://github.com/Atcold/NYU-DLSP20/blob/master/slides/12%20-%20EBM.pdf) </span>
- <span class="missing"> 13 – Training LV-EBMs [🎥](https://youtu.be/XIMaWj5YjOQ) [🖥](https://github.com/Atcold/NYU-DLSP20/blob/master/slides/12%20-%20EBM.pdf) </span>
- 14 – From latent-variable EBMs (K-means, sparse coding), to target propagation to autoencoders [🎥](https://youtu.be/oo9Z9jKJ9iM) [🖥](https://drive.google.com/file/d/1eAFH58VazIdpEPfkD_xDNadQe7Jss_uY/)

---

① I did create some new RNN diagrams (see [tweet](https://twitter.com/alfcnz/status/1448005146684928005) and quoted one), so this lesson may get published, at some time. For now I'm focussing on the energy lessons first.
