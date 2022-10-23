---
layout: post
title: Quasi-Normal Coupled Mode Theory
date: 2022-10-23 16:39:00
description: Rigorous coupled mode theory for general scattering problem
tags: math linear_algebra physics
categories: math
---

The coupled mode theory (CMT) has not been treated systematically in lossy and irreciprocal scattering problem and is normally
used in an intuitive manner. As a result, we need to formalize the so called quasi-normal coupled mode theory (QCMT) to be consistent with the scattering in low-Q, dispersive and irreciprocal scenario.

This post refers the following two papers:
- [Quasi-normal Coupled Mode Theory](https://arxiv.org/abs/2010.08650)
- [Light Interaction with Photonic and Plasmonic Resonances](https://onlinelibrary.wiley.com/doi/10.1002/lpor.201700113)

<figure>
  <center>
  <img src="/assets/img/posts_img/scattering_problem.jpg" width="450" height="200">
  <figcaption> A schematic figure of a general scattering problem.</figcaption>
  </center>
</figure>

In a general scattering problem, the discrepance from a Hermitian problem could stem from
- Non-Hermitian Operator: Lossy; Dispersivel irreciprocal
- Non-Hermitian Boundary Conditions: Open Boundary

The general scattering prblem could be described by the following dynamic equation:

$$\underbrace{\left(\begin{array}{cc}
&\nabla \cdot \\ \nabla \cdot &
\end{array}\right)}_{\Theta} \underbrace{\left(\begin{array}{c}
\boldsymbol{Q} \\
\boldsymbol{P}
\end{array}\right)}_\psi-\dfrac{\partial}{\partial t} \left(\underbrace{\left(\begin{array}{cc}
1 & 0 \\
0 & -1
\end{array}\right)+\Delta B}_B\right)\left(\begin{array}{c}
\boldsymbol{Q} \\
\boldsymbol{P}
\end{array}\right)=-\underbrace{\left(\begin{array}{c}
\boldsymbol{J}_q \\
-\boldsymbol{J}_p
\end{array}\right)}_{\xi}$$

The eigenmodes of such a problem, in general, form a complete orthonormal basis to describe fields in the scatter in the following manner:

$$
\begin{aligned}
\Theta \psi_{\mathrm{R}, m} &=\mathrm{i} \widetilde{\omega}_m B\left(\widetilde{\omega}_m\right) \psi_{\mathrm{R}, m} \\
\Theta \psi_{\mathrm{L}, n} &=\mathrm{i} \widetilde{\omega}_n B^T\left(\widetilde{\omega}_n\right) \psi_{\mathrm{L}, n}\\
\int_V \psi_{\mathrm{L}, n}^T B \psi_{\mathrm{R}, n}&=1.
\end{aligned}
$$

With the above, the description of the coupled mode theory could extend to broader cases. The validity of conventional CMT could be checked in the rigorous derivations as well. The exact QCMT theory allows us to uniquely answer this question. The QCMT theory reduces to conventional CMT when the following conditions hold:
1. The Born-scattering background term is small.
2. The coupling strengths must be approximately frequency-independent over the bandwidth of interest.

The later is a more precise statement of the well-understood requirement that CMT requires high-quality-factor, well-separated resonances.

Please check the attached [slides](/assets/img/posts_img/QCMT.pptx) for details.
