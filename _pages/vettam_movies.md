---
title: "Movies: VETTAM RHD Code"
permalink: /vettam_movies/
author_profile: true
classes: wide
---

Below are some movies of some tests performed in the [**VETTAM Method Paper**](https://ui.adsabs.harvard.edu/abs/2022MNRAS.512..401M/abstract). Please refer to the paper for a full description of the tests and the initial conditions.

<h3><u>
  Transport of Gaussian pulse in the streaming, static and dynamic diffusion regimes
</u> </h3>

This test demonstrates that VETTAM can handle *all asymptotic limits of radiation hydrodynamics. It shows the propogation of a Gaussian pulse of radiation energy in optically thin/streaming conditions (left), in moderately optically thick/static diffusion conditions (middle), and in extremely optically thick/dynamic diffusion regime (right). Different linestyles denote different grid resolutions and the purple dashed lines shows the analytical solution. This test is described in Section 3.1 of our paper.

<video muted controls width="900" controls="controls">
  <source src="/assets/videos/GaussianPulse.mp4" type="video/mp4" caption="GaussianPulse" allowfullscreen>
  This video cannot be played.
</video>

<h3><u>
  Infrared radiation-pressure driven shell expansion
</u> </h3>

Animation showing the evolution of the projected gas density for the thin shell expansion test in Section 3.7 of our paper. There is a source of (IR) radiation at the centre, and a dusty shell at t = 0. The IR photons scatter through the shell and drive the expansion of the shell in very good agreement with analytical predictions. We also use AMR for this test, where we focus the resolution on the thin shell; the movie shows the block structure of the grid.
<video muted controls width="95%" controls="controls" loop>
  <source src="/assets/videos/ThinShell_Movie.mp4" type="video/mp4">
</video>

<h3><u>
  Shadow cast by two point sources of radiation: Comparison of different closures
</u> </h3>

The animation below shows the evolution of gas temperature as two point-like sources of light impinges on a dense spherical blob of gas. The evolution obtained with VETTAM (right panel) is compared with that obtained with more commonly used, but less accurate closures such as FLD and M1. This is the test described in Section 3.8.2 of our paper. We can see that VETTAM produces the right solution for this scenario, whereas the other closures fail to do so.
<video muted controls width="95%" controls="controls" loop>
  <source src="/assets/videos/temp_comparemethods.mp4" type="video/mp4">
</video>


<h3><u>
  Shadow cast by an extended diffuse source of radiation
</u> </h3>

The animation below shows the evolution of gas temperature as an extended hot source at the bottom of the domain impinges on a dense spherical blob of gas at the top of the domain. This is the test described in Section 3.8.3 of our paper. We can see that VETTAM produces that seem qualitatively correct for the given distribution.
<video muted controls width="95%" controls="controls" loop>
  <source src="/assets/videos/temp_nSide4.mp4" type="video/mp4">
</video>

