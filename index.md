---
title: Home
---

<img src="{{site.baseurl}}/images/banner.png">

## Abstract

[comment]: <> (<img align="right" src="https://github.com/vios-s/adversarial-test-time-training/blob/master/method.pdf" width=100>)

Thanks to their ability to learn data distributions without requiring paired data, Generative Adversarial Networks (GANs) have become an integral part of many computer vision methods, including those developed for medical image segmentation. These methods jointly train a segmentor and an adversarial mask discriminator, which provides a data-driven shape prior. At inference, the discriminator is discarded, and only the segmentor is used to predict label maps on test images. But should we discard the discriminator? Here, we argue that the life cycle of adversarial discriminators should not end after training. On the contrary, training stable GANs produces powerful shape priors that we can use to correct segmentor mistakes at inference. To achieve this, we develop stable mask discriminators that do not overfit or catastrophically forget. At test time, we fine-tune the segmentor on each individual test instance until it satisfies the learned shape prior. Our method is simple to implement and increases model performance. Moreover, it opens new directions for re-using mask discriminators at inference. 

## Keywords
**GAN** &nbsp; | &nbsp;
**Segmentation** &nbsp; | &nbsp;
**Test-time training** &nbsp; | &nbsp;
**Shape prior** &nbsp;

## Cite us:
```
@incollection{valvano2021selfsup,
      title={Stop Throwing Away Discriminators! Re-using Adversaries for Test-Time Training}, 
      author={Gabriele Valvano and Andrea Leo and Sotirios A. Tsaftaris},
      year={2021},
      booktitle={Domain Adaptation and Representation Transfer},
}

```

## Don't miss any update!
**You can either:**
 - **write us an** [**email**](https://vios-s.github.io/adversarial-test-time-training/contacts), and we will answer back
 - or **watch the** [**GitHub**](https://github.com/gvalvano/adversarial-test-time-trainingg) repository for updates on the *code*

