---
title: "Movies of Simulations"
permalink: /movies/
author_profile: true
classes: wide
layout: splash

feature_row:
  - image_path: /assets/images/ExtendedSource.png
    alt: "placeholder image 1"
    title: "VETTAM Test Movies"
    url: "/movies/#vettam"
    excerpt: "RHD tests performed in the [VETTAM Method Paper](https://ui.adsabs.harvard.edu/abs/2022MNRAS.512..401M/abstract)"
    btn_label: "Click here to see"
    btn_class: "btn--info btn--large"
  - image_path:  /assets/images/RK16.png
    alt: "placeholder image 2"
    title: "RHD Simulations of Super-Star Cluster Formation"
    url: "/movies/#rhd-simulations-of-super-star-cluster-formation"
    excerpt: "Simulations from [Menon+ 2022b.](https://ui.adsabs.harvard.edu/abs/2022arXiv220614190M/abstract) and Menon+ 2022c (in prep.)"
    btn_label: "Click here to see"
    btn_class: "btn--info btn--large"
  - image_path: /assets/images/Ionize_ZColumn.png
    title: "Turbulent ISM Shaped by Ionising Radiation"
    url: "/movies/#interaction-of-ionising-radiation-with-the-turbulent-ism"
    excerpt: "Simulations performed in [Menon+ 2020](https://ui.adsabs.harvard.edu/abs/2020MNRAS.493.4643M/abstract)."
    btn_label: "Click here to see"
    btn_class: "btn--info btn--large"
---

{% include feature_row %} 

VETTAM Test Simulations
------

Below are some movies of some tests performed in the [**VETTAM Method Paper**](https://ui.adsabs.harvard.edu/abs/2022MNRAS.512..401M/abstract). Please refer to the paper for a full description of the tests and the initial conditions.

<h4><u>
  Transport of Gaussian pulse in the streaming, static and dynamic diffusion regimes
</u> </h4>

This test demonstrates that VETTAM can handle *all asymptotic limits of radiation hydrodynamics. It shows the propogation of a Gaussian pulse of radiation energy in optically thin/streaming conditions (left), in moderately optically thick/static diffusion conditions (middle), and in extremely optically thick/dynamic diffusion regime (right). Different linestyles denote different grid resolutions and the purple dashed lines shows the analytical solution. This test is described in Section 3.1 of our paper.

<video muted controls width="900" controls="controls">
  <source src="/assets/videos/GaussianPulse.mp4" type="video/mp4" caption="GaussianPulse" allowfullscreen>
  This video cannot be played.
</video>

<h4><u>
  Infrared radiation-pressure driven shell expansion
</u> </h4>

Animation showing the evolution of the projected gas density for the thin shell expansion test in Section 3.7 of our paper. There is a source of (IR) radiation at the centre, and a dusty shell at t = 0. The IR photons scatter through the shell and drive the expansion of the shell in very good agreement with analytical predictions. We also use AMR for this test, where we focus the resolution on the thin shell; the movie shows the block structure of the grid.
<video muted controls width="95%" controls="controls" loop>
  <source src="/assets/videos/ThinShell_Movie.mp4" type="video/mp4">
</video>

<h4><u>
  Shadow cast by two point sources of radiation: Comparison of different closures
</u> </h4>

The animation below shows the evolution of gas temperature as two point-like sources of light impinges on a dense spherical blob of gas. The evolution obtained with VETTAM (right panel) is compared with that obtained with more commonly used, but less accurate closures such as FLD and M1. This is the test described in Section 3.8.2 of our paper. We can see that VETTAM produces the right solution for this scenario, whereas the other closures fail to do so.
<video muted controls width="95%" controls="controls" loop>
  <source src="/assets/videos/temp_comparemethods.mp4" type="video/mp4">
</video>


<h4><u>
  Shadow cast by an extended diffuse source of radiation
</u> </h4>

The animation below shows the evolution of gas temperature as an extended hot source at the bottom of the domain impinges on a dense spherical blob of gas at the top of the domain. This is the test described in Section 3.8.3 of our paper. We can see that VETTAM produces that seem qualitatively correct for the given distribution.
<video muted controls width="95%" controls="controls" loop>
  <source src="/assets/videos/temp_nSide4.mp4" type="video/mp4">
</video>

---

RHD Simulations of Super Star Cluster Formation
------

<h4><u>
  Gas Evolution
</u> </h4>

Simulations from [Menon+ 2022c](https://ui.adsabs.harvard.edu/abs/2022arXiv220614190M/abstract) showing the evolution of the projected gas density under the effects of UV+IR radiation pressure, for four different initial gas surface densities (increasing top-left to bottom-right).

<video muted controls width="1000" controls="controls">
  <source src="/assets/videos/CompareSigma_Multiband.mp4" type="video/mp4" caption="TEST" allowfullscreen>
  This video cannot be played.
</video>

<h4><u>
  UV vs IR
</u> </h4>

Comparing the evolution of gas for control simulations with only the radiation pressure in the IR band (left), UV band (middle), and the combined UV and IR radiation bands (right).

<video muted controls width="1200" controls="controls">
  <source src="/assets/videos/Sigma3.2e3_UV_Vs_IR.mp4" type="video/mp4">
</video>

<h4><u>
  Dust-to-gas ratios
</u> </h4>

Simulations from [Menon+ 2022b](https://ui.adsabs.harvard.edu/abs/2022arXiv220614190M/abstract) showing the evolution of the projected gas density, compared for dust to gas ratios of 1, 2 and 3 times solar respectively (left to right). We can see that even at high dust-to-gas ratios, the effects of IR radiation on the dynamics are mild.

<video muted controls width="1200" controls="controls">
  <source src="/assets/videos/Sigma3.2e4_DGCompare.mp4" type="video/mp4">
</video>


<h4><u>
  IR dust opacities
</u> </h4>

Movies of simulations for our fiducial run in [Menon+ 2022b](https://ui.adsabs.harvard.edu/abs/2022arXiv220614190M/abstract) with realistic dust opacities of Semenov et al. 2003 (left) used in our simulation setup. This is compared with control runs that adopt a power-law approximation to the same (middle), and a run with a constant dust opacity of 10 cm^2 g^-1 (right): both of which are commonly used approximations in the literature. The difference in dynamical outcomes shows why using the dust IR opacities consistent with the state of the gas are important.

<video muted controls width="1200" controls="controls">
  <source src="/assets/videos/Sigma3.2e5_Opacs.mp4" type="video/mp4">
</video>


---

Interaction of ionising radiation with the turbulent ISM
------
Simulations from [**Menon, Federrath & Kuiper 2020**](https://ui.adsabs.harvard.edu/abs/2020MNRAS.493.4643M/abstract) of a turbulent cloud impinged by a plane-parallel front of ionising radiation coming in from the left boundary. The movie shows the line-of-sight column density of the gas perpendicular (left) and parallel (right) to the direction of the incoming radiation front. The radiation ionises the low-density gas/voids in the turbulent cloud, heating that gas to 10000 K, whose increased thermal pressure compresses the overdensities that are still neutral. This produces pillar-like neutral gas structures, reminiscent of the famous "Pillars of Creation". 

<video muted autoplay controls width="95%" controls="controls">
  <source src="/assets/videos/UVTurbulence.mp4" type="video/mp4">
</video>
