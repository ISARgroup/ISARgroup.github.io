---
layout: post
title:  "Slides and Correction for INTERSPEECH 2026 Paper"
---

### Slides and Correction for INTERSPEECH 2026 Paper
### Label Correction Enhanced Dual-Stream Multiple Instance Learning for Weakly-Supervised Depression Detection in Speech

<br>

- Paper:
Sun Y, Zhou Y, Xu X, Qi J, Xu F, Ren Z, Schuller B. Label Correction Enhanced Dual-Stream Multiple Instance Learning for Weakly-Supervised Depression Detection in Speech[C]//Proc. INTERSPEECH, 2026: 5044-5049. [Link](https://www.isca-archive.org/interspeech_2026/sun26e_interspeech.html)

<br>

The slides can be downloaded via: [GitHub Link](https://github.com/ISARgroup/ISARgroup.github.io/blob/master/Wed_1716_C2.5_XinzhouXu_v4.pdf)

<br>
<br>

Correction (see the paper): 

1) Page 2 (Left): "we flip the origin label to obtain" to "we flip the original label to obtain";
2) Page 3 (Left): "$\tilde{\mathbf{q}}^{(c)}=\operatorname{tanh}(\mathbf{W}_q \tilde{\mathbf{q}}^{(c)}+\mathbf{b}_q)$" to "$\tilde{\mathbf{q}}^{(c)}=\operatorname{tanh}(\mathbf{W}_q \tilde{\mathbf{a}}^{(c)}+\mathbf{b}_q)$";
3) Page 3 (Left, Equation (9)): "p({\bf s}) = \mu p^{(M)}(\mathbf{s}) + (1-\mu)p^{(A)}(\mathbf{s})," to "p({\bf s}) = \operatorname{softmax}\left(\mu p^{(M)}(\mathbf{s}) + (1-\mu)p^{(A)}(\mathbf{s})\right),";
4) Page 4 (Left, the end of Section 3.2): Adding "Note that all the comparisons and ablation results for the proposed LC-DMIL are chosen corresponding to the best UARs within the epochs in training the MIL-based depression detection module.".



<br>


Please contact: xinzhou.xu@njupt.edu.cn
