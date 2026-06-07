---
title: "Research Summary"
permalink: /posts/
author_profile: False
header:
  overlay_image: /assets/images/Carina.png
  caption: "Photo credit: [**James Webb Space Telescope**](https://webbtelescope.org/contents/media/images/2022/031/01G77PKB8NKR7S8Z6HBXMYATGJ)"
  overlay_filter: 0.4
layout: splash
classes: wide
intro:
  - excerpt: 'My research broadly focuses on understanding the interplay of star formation and stellar feedback in the interstellar medium (ISM) — a critical piece in our understanding of how galaxies form stars and evolve over cosmic time. I use a combination of numerical simulations, theoretical modelling, and observational comparisons to study this problem, with a particular emphasis on extreme environments in the early Universe. A core part of my work involves the development of state-of-the-art numerical algorithms for modelling feedback in hydrodynamic simulations.'

feature_row:
- image_path: /assets/images/StarClusterSim.png
  title: "Dense stellar cluster formation and evolution"
  excerpt: "I study the formation of massive star clusters and the effects of stellar feedback on regulating star formation and the thermochemical and dynamical state of the surrounding gas and dust. I run controlled radiation hydrodynamical simulations spanning a range of environmental conditions, and build on their insights to develop (semi-)analytic models and synthetic observations that provide interpretive power for current and upcoming observational facilities. A particular focus of my recent work has been on the extremely dense, compact star clusters observed at Cosmic Dawn with JWST, and the disproportionately important role they may play in controlling the evolution and observable properties of their host galaxies. <br/> Papers: [**Menon & Smith 26**](https://ui.adsabs.harvard.edu/abs/2026arXiv260513982M/abstract), [**Menon+25**](https://ui.adsabs.harvard.edu/abs/2024arXiv240814591M/abstract), [**Menon+24**](https://ui.adsabs.harvard.edu/abs/2024ApJ...967L..28M/abstract), [**Menon+23**](https://ui.adsabs.harvard.edu/abs/2022arXiv221002818M/abstract), [**Menon+22**](https://ui.adsabs.harvard.edu/abs/2022arXiv220614190M/abstract), [**Somerville+25**](https://ui.adsabs.harvard.edu/abs/2025MNRAS.544.3774S/abstract)"
- image_path: /assets/images/PopIIIsim.png
  title: "Star formation and the initial mass function in the early Universe"
  excerpt: "The stellar initial mass function (IMF) — the distribution of stellar masses at birth — is a foundational assumption in virtually all of astrophysics, yet its universality, especially under the extreme conditions of the early Universe, remains an open question. I am co-I of the [**POPSICLE**](https://ui.adsabs.harvard.edu/abs/2025MNRAS.540.1745S/abstract) project where we study how the IMF and stellar populations change in the low-metallicity and dense conditions of Pop III/Pop II star-forming regions. We use RMHD simulations coupled to primordial and metal chemical networks designed for low-metallicity environments for this work, to explore implications on early galaxies, chemical enrichment and metal-poor stellar populations. <br/> Papers: [**Sharda & Menon 2024**](https://ui.adsabs.harvard.edu/abs/2024arXiv240518265S/abstract), [**Sharda+25**](https://ui.adsabs.harvard.edu/abs/2025arXiv250112734S/abstract),[**Chen+26**](https://ui.adsabs.harvard.edu/abs/2026arXiv260400197C/abstract), [**Eriksson+25**](https://ui.adsabs.harvard.edu/abs/2025MNRAS.542..641E/abstract), [**van Veenen+26**](https://ui.adsabs.harvard.edu/abs/2026A%26A...708A..61V/abstract)"
- image_path: /assets/images/VET_M1.png
  title: "Development of numerical schemes to model stellar feedback"
  excerpt: "To study the effects of stellar feedback one needs accurate and efficient numerical methods. In particular to model how radiation propogates in a moving fluid -- i.e. radiation hydrodynamics (RHD). In my PhD, I developed [**VETTAM**](https://ui.adsabs.harvard.edu/abs/2022MNRAS.512..401M/abstract), an openly accessible algorithm coupled to the FLASH MHD code to model how radiation propogates in a moving fluid (RHD). VETTAM is the state-of-the-art in the field due to its accuracy in modelling radiation fields in general configurations, and its flexibility to handle more extreme regimes that cannot realistically be modelled with most other existing methods. More recently, we have coupled VETTAM to a range of thermochemistry implementations with the KROME framework to capture time-dependent photodissociation regions (PDRs) and HII regions in the ISM.  <br/> Papers: [**Menon+22**](https://ui.adsabs.harvard.edu/abs/2022MNRAS.512..401M/abstract),[**Menon+26, in prep**]"
- image_path: /assets/images/Ionize_ZColumn.png
  title: "How does radiation feedback shape the properties of the turbulent ISM?"
  excerpt: "The momentum and energy in massive star radiation feedback can significantly alter the conditions of the gas surrounding these stars/clusters, giving rise to  incredibly picturesque structures such as the Pillars of Creation in the Eagle Nebula, or the more recent JWST image of the Carina Nebula. Using RHD simulations and observational comparisons, we quantify how the radiation field sculpts the density field in such environments, and what kind of turbulent motions are produced in them. This has consequences for how we can interpret the structures in these regions, and how future star formation would proceed in them. <br/> Papers: [**Menon+ 21**](https://ui.adsabs.harvard.edu/abs/2021MNRAS.500.1721M/abstract), [**Menon+20**](https://ui.adsabs.harvard.edu/abs/2020MNRAS.493.4643M/abstract), [**Sharda+22**](https://ui.adsabs.harvard.edu/abs/2022MNRAS.509.2180S/abstract)"
- image_path: /assets/images/NGC_1313_galaxyImage.png
  title: "Why is star formation distributed the way it is in galaxies?"
  excerpt: "Star formation is distributed in a clumpy, hierarchical fashion in galaxies, and probing differences in their distributions can offer insights into the dominant physical mechanisms at play for star formation. I study, along with, and using data from, collaborations like such as LEGUS, HiPEEC, and most recently PHANGS, to probe such differences across galaxies. I use the two-point correlation function (TPCF) to quantify the clustered nature of star formation, and compare with toy model distributions to interpret what they might resemble. <br/> Papers: [**Menon+21**](https://ui.adsabs.harvard.edu/abs/2021MNRAS.507.5542M/abstract), [**Ananthu+26**](https://ui.adsabs.harvard.edu/abs/2026ApJ..1002..220A/abstract), [**Shashank+25**](https://ui.adsabs.harvard.edu/abs/2025A%26A...693A.188S/abstract)"
- image_path: /assets/images/HIFrag.png
  title: "The self-regulated formation of cold gas in the ISM via the thermal instability, shear and feedback."
  excerpt: "The star-forming dense, cold phase of in the ISM (i.e., the Cold Neutral Medium; CNM) forms and evolves amidst a combination of physical mechanisms operating at galactic scales: namely, the thermal instability, differential rotation/shear and stellar feedback. In my master's thesis, I performed numerical simulations with the *Athena* MHD code to explore how each of these mechanisms individually affects the formation and fragmentation of the CNM, and how the process of CNM formation and destruction is self-regulating over ~Gyr timescales <br/> [**Link to Master's Thesis**](https://www.dropbox.com/sh/afarzv6v6pvqyes/AACdRiKa9tuUTN-Z_GbyU1Qfa?dl=0)"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row type="left" %} 






