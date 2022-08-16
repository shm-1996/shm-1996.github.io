---
title: "VETTAM: a state-of-the-art radiation hydrodynamics scheme"
permalink: /vettam/
author_profile: True
layout: splash
classes: wide
---

<h3><u>
  VETTAM: a state-of-the-art radiation hydrodynamics scheme
</u> </h3>
Studying the role of stellar feedback requires solving the complicated equations that govern the coupled dynamics of gas/dust along with the transport of radiation through this medium, i.e. the radiation hydrodynamic equations. This requires one to resort to numerical methods, and hence, developing accurate, well-performing numerical algorithms for radiation hydrodynamics is crucial. This is made complicated due to the non-local nature of radiation transport, and the vastly different timescales at which photons and gas propogate through a medium. In this context, I led the development of VETTAM -- a novel, state-of-the-art radiation hydrodynamics scheme coupled to the FLASH magnetohydrodynamics code. VETTAM is an acronym for *Variable Eddington Tensor closed-Transport on Adaptive Meshes*, and means "light" in the south-Indian language of Malayalam, which happens to be my first language.

VETTAM is unique as it uses the so-called Variable Eddington Tensor closure method for radiation transport, that vastly improves on earlier schemes that use more approximate methods, which have been shown to lead to inaccurate and (sometimes) unphysical radiation fields and dynamical effects in certain situations that are relevant to the turbulent ISM. In addition, VETTAM uses an implicit temporal update for the radiation fields, which, unlike most other schemes in the literature that use the so-called reduced speed of light approximation (RSLA), can be used in conditions of high optical depth -- crucial to study systems such as starburst environments, dense star-forming regions etc. VETTAM uses the open-source PETSC library for the implicit temporal updates, which require matrix inversions using sparse Krylov solvers. This enables strong performance and scaling, which would continue to improve as the algorithms in the library are updated, along with providing flexibility through a multitude of solvers and preconditioners that could be used for a specific problem. 

{% include figure image_path="/assets/images/VETMethodCompare.pdf" caption="The radiation field obtained with the VET method (right) compared with the more commonly adopted FLD (left) or Moment-1 (right) approximations, for a test of two sources of radiation in an optically thin medium, impinging on an optically thick spherical blob of gas. Figure adopted from " %}