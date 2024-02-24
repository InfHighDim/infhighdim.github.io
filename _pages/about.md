---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

My name is Dewei Li. I was born in April 1991 and my hometown is Lingbi County, Anhui Province. I have received the bachelor’s degree and master’s degree from Renmin University of China in 2012 and 2015 respectively, and the Ph.D. degree from University of Chinese Academy of Sciences in 2018. I have worked as Senior Engineer in Huawei and Tencent. My E-mail is lidewei06@163.com.

Research Interests
======
My current research interests focus on machine learning and optimization, including metric learning, contrastive learning.
* **Metric learning**: The topic aims to learn a transformation to map the original data into a new space, in which the distance between similar samples become smaller and that of dissimilar samples become larger.([Demo](https://infhighdim.github.io/metric_demo/))

<img src="https://infhighdim.github.io/images/metric_learn_concept.png" class="floatpic" width="520" height="155">

&emsp;&emsp;(1) **Traditional Metric Learning**: Learning a semi-definite matrix $M$ to redefine the distance between any two samples using
 Generalized Mahalanobis Distance $$d(x_i, x_j) = \sqrt{(x_i - x_j)^\top M(x_i - x_j)}$$
 
&emsp;&emsp;(2) **Deep Metric Learning**: Learning a nonliear mapping $f(x)$ by a deep neural networks and compute distance by $d(x_i, x_j) = \sqrt{(f(x_i) - f(x_j))^\top (f(x_i) - f(x_j))}$.

* **Contrastive Learning**: It aims to deal with self-supervised task, using metric learning and deep learning methods.
<img src="https://infhighdim.github.io/images/contrastive_concept.png" class="floatpic" width="595" height="370">





Wecome! You are the ![Visitor Count](https://profile-counter.glitch.me/InfHighDim/count.svg) visitor!
