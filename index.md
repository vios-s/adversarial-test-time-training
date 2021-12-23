---
title: Adversarial Test-Time Training
---

<img src="{{site.baseurl}}/images/banner.png">

## Abstract

[comment]: <> (<img align="right" src="https://github.com/vios-s/adversarial-test-time-training/blob/master/method.pdf" width=100>)

Thanks to their ability to learn flexible data-driven losses, Generative Adversarial Networks (GANs) are an integral part of many semi- and weakly-supervised methods for medical image segmentation. GANs jointly optimise a generator and an adversarial discriminator on a set of training data. After training has completed, the discriminator is usually discarded and only the generator is used for inference. But should we discard discriminators? In this work, we argue that training stable discriminators produces expressive loss functions that we can re-use at inference to detect and correct segmentation mistakes. First, we identify key challenges and suggest possible solutions to make discriminators re-usable at inference. Then, we show that we can combine discriminators with image reconstruction costs (via decoders) to further improve the model. Our method is simple and improves the test-time performance of pre-trained GANs. Moreover, we show that it is compatible with standard post-processing techniques and it has potentials to be used for Online Continual Learning. With our work, we open new research avenues for re-using adversarial discriminators at inference
## Keywords
**GAN** &nbsp; | &nbsp;
**Segmentation** &nbsp; | &nbsp;
**Test-time training** &nbsp; | &nbsp;
**Shape prior** &nbsp;

## Cite us:
```
@incollection{valvano2021stop,
  title={Stop Throwing Away Discriminators! Re-using Adversaries for Test-Time Training},
  author={Valvano, Gabriele and Leo, Andrea and Tsaftaris, Sotirios A},
  booktitle={Domain Adaptation and Representation Transfer, and Affordable Healthcare and AI for Resource Diverse Global Health},
  pages={68--78},
  year={2021},
  publisher={Springer}
}
```

An extended version of the manuscript can be found [here](https://arxiv.org/abs/2108.11926), and cited as:
```
@article{valvano2021re,
  title={Re-using Adversarial Mask Discriminators for Test-time Training under Distribution Shifts},
  author={Valvano, Gabriele and Leo, Andrea and Tsaftaris, Sotirios A},
  journal={arXiv preprint arXiv:2108.11926},
  year={2021}
}
```

## Don't miss any update!
**You can either:**
 - **write us an** [**email**](https://vios-s.github.io/adversarial-test-time-training/contacts), and we will answer back
 - or **watch the** [**GitHub**](https://github.com/gvalvano/adversarial-test-time-trainingg) repository for updates on the *code*

