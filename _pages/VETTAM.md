---
title: "VETTAM: a state-of-the-art radiation hydrodynamics scheme"
permalink: /vettam/
author_profile: True
layout: splash
classes: wide
---

<style type="text/css">
    .image-left {
      display: block;
      margin-left: auto;
      margin-right: auto;
      float: right;
    }
</style>

<h3><u>
  VETTAM: a state-of-the-art radiation hydrodynamics scheme
</u> </h3>
Studying the role of stellar feedback requires solving the complicated equations that govern the coupled dynamics of gas/dust along with the transport of radiation through this medium, i.e. the radiation hydrodynamic equations. This requires one to resort to numerical methods, and hence, developing accurate, well-performing numerical algorithms for radiation hydrodynamics is crucial. This is made complicated due to the non-local nature of radiation transport, and the vastly different timescales at which photons and gas propogate through a medium. In this context, I led the development of **VETTAM -- a novel, state-of-the-art radiation hydrodynamics scheme coupled to the FLASH magnetohydrodynamics code**. VETTAM is an acronym for *Variable Eddington Tensor closed-Transport on Adaptive Meshes*, and means "light" in the south-Indian language of Malayalam, which happens to be my first language.

VETTAM is unique as it uses the so-called Variable Eddington Tensor closure method for radiation transport, that vastly improves on earlier schemes that use more approximate methods, which have been shown to lead to inaccurate and (sometimes) unphysical radiation fields and dynamical effects in certain situations that are relevant to the turbulent ISM. In addition, VETTAM uses an implicit temporal update for the radiation fields, which, unlike most other schemes in the literature that use the so-called reduced speed of light approximation (RSLA), can be used in conditions of high optical depth -- crucial to study systems such as starburst environments, dense star-forming regions etc. VETTAM uses the open-source PETSC library for the implicit temporal updates, which require matrix inversions using sparse Krylov solvers. This enables strong performance and scaling, which would continue to improve as the algorithms in the library are updated, along with providing flexibility through a multitude of solvers and preconditioners that could be used for a specific problem. 

{% include figure image_path="/assets/images/VETMethodCompare.pdf" caption="The radiation field obtained with the VET method (right) compared with the more commonly adopted FLD (left) or Moment-1 (right) approximations, for a test of two sources of radiation in an optically thin medium, impinging on an optically thick spherical blob of gas. Figure adopted from [**Menon et al. 2022, MNRAS, 512, 401**](https://ui.adsabs.harvard.edu/abs/2022MNRAS.512..401M/abstract)" %}


<video muted controls width="500" style="float:right;"> <source src="/assets/videos/temp_nSide4.mp4" type="video/mp4"> </video>
  <p> In addition to non-trivial point source distributions, the VET-closure used in VETTAM also provides the correct solution for extended sources of radiation. For example, the animation on the right shows the gas temperature evolution for a clump of gas impinged by radiation from an extended hot medium (for instance, an accretion disk), producing sharp shadows, and subtle features such as the umbra and penumbra. Most other methods in the literature which use the FLD or M1 closures would not be able to produce the correct solution here. </p>

VETTAM currently has support for modeling all relevant radiative feedback mechanisms for star formation/ISM applications. The animation below demonstrates the flexibility of VETTAM and various applications that it could be used for in the context of these fields. The inclusion of additional radiative mechanisms (e.g. Thompson scattering) should be relatively straightforward due to a vastly modular design used in VETTAM/FLASH.
<video muted controls width="1200" controls="controls">
  <source src="/assets/videos/VETTAM_Bands.mp4" type="video/mp4" caption="GaussianPulse" allowfullscreen>
  This video cannot be played.
</video>
Left: Star cluster formation/evolution simulation under the influence of UV radiation pressure and simulated with VETTAM, with the initial conditions mimicking the fiducial simulation in [**Raskutti et al. 2016**](https://ui.adsabs.harvard.edu/abs/2016ApJ...829..130R/abstract). Middle: Same as before, but for IR radiation pressure, and initial conditions mimicking the fiducial simulation in [**Skinner & Ostriker 2015**](https://ui.adsabs.harvard.edu/abs/2015ApJ...809..187S/abstract). Right: a test simulation of a plane-parallel front of photoionizing radiation impinging on a turbulent cloud run with VETTAM, with a setup similar to [**Menon, Federrath & Kuiper 2020, MNRAS, 493, 4643**](https://ui.adsabs.harvard.edu/abs/2020MNRAS.493.4643M/abstract).

<a href="https://ui.adsabs.harvard.edu/abs/2022MNRAS.512..401M/abstract" class="btn btn--primary">VETTAM Method Paper</a> <a href="/vettam_movies" class="btn btn--primary">Simulation Movies</a>  
