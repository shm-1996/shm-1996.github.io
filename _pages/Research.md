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
  - excerpt: 'My research focuses on understanding how the feedback from massive stars couples to the surrounding interstellar medium, and how that impacts the formation of stars and the evolution of gas in galaxies. I use a combination of numerical simulations, theoretical modelling and observational comparisons for studying this problem. A crucial part of my research involves the development of state-of-the-art numerical algorithms for modelling feedback in numerical hydrodynamic simulations.'

feature_row:
- image_path: /assets/images/ExtendedSource.png
  title: "Development of numerical radiation hydrodynamics schemes to model radiation feedback"
  excerpt: "To study the effects of stellar feedback one needs accurate numerical methods to model how radiation propogates in a moving fluid -- i.e. radiation hydrodynamics (RHD). For this, I developed [**VETTAM**](https://ui.adsabs.harvard.edu/abs/2022MNRAS.512..401M/abstract), an RHD algorithm that is coupled to the FLASH MHD code. VETTAM is the state-of-the-art in the field due to its accuracy in modelling radiation fields in general configurations, and its flexibility to handle more extreme regimes that cannot realistically be modelled with most other existing methods. <br/> Papers: [**Menon et al. 2022, MNRAS, 512, 401**](https://ui.adsabs.harvard.edu/abs/2022MNRAS.512..401M/abstract)"
  url: /vettam/
  btn_label: "Read More"
  btn_class: "btn--primary"
- image_path: /assets/images/RK16.png
  title: "What role can radiation pressure play in regulating star formation and driving winds"
  excerpt: "The momentum imparted to the ISM through the absorption of stellar UV/optical radiation by dust grains is an important feedback mechanism, especially in denser star-forming regions, as it can provide a support against gravitational collapse and thereby regulate star formation and drive winds. In addition, at high surface densities, the dust-reprocessed IR radiation can play a significant, and sometimes dominant, role in this process. We study, with numerical RHD simulations, how effective radiation pressure is in regulating star formation and/or driving outflows in regimes that resemble super-star clusters found in starburst environments. <br/> Papers: [**Menon, Federrath & Krumholz 2022a, MNRAS, subm.**](https://ui.adsabs.harvard.edu/abs/2022arXiv220614190M/abstract), [**Menon, Federrath & Krumholz 2022b, MNRAS, subm.**](https://ui.adsabs.harvard.edu/abs/2022arXiv220614190M/abstract)"
  url: /radpressure/
  btn_label: "Read More"
  btn_class: "btn--primary"
- image_path: /assets/images/Ionize_ZColumn.png
  title: "How does radiation feedback shape the properties of the turbulent ISM?"
  excerpt: "The momentum and energy in massive star radiation feedback can significantly alter the conditions of the gas surrounding these stars/clusters, giving rise to  incredibly picturesque structures such as the Pillars of Creation in the Eagle Nebula, or the more recent JWST image of the Carina Nebula. Using RHD simulations and observational comparisons, we quantify how the radiation field sculpts the density field in such environments, and what kind of turbulent motions are produced in them. This has consequences for how we can interpret the structures in these regions, and how future star formation would proceed in them. <br/> Papers: [**Menon, Federrath & Kuiper 2020, MNRAS, 493, 4643**](https://ui.adsabs.harvard.edu/abs/2020MNRAS.493.4643M/abstract), [**Menon et al. 2021, MNRAS, 500, 1721**](https://ui.adsabs.harvard.edu/abs/2021MNRAS.500.1721M/abstract)"
  url: /ionturb/
  btn_label: "Read More"
  btn_class: "btn--primary"
- image_path: /assets/images/NGC_1313_galaxyImage.png
  title: "Why is star formation distributed the way it is in galaxies?"
  excerpt: "Star formation is distributed in a clumpy, hierarchical fashion in galaxies, and probing differences in their distributions can offer insights into the dominant physical mechanisms at play for star formation. I study, along with, and using data from, collaborations like such as LEGUS, HiPEEC, and most recently PHANGS, to probe such differences across galaxies. I use the two-point correlation function (TPCF) to quantify the clustered nature of star formation, and compare with toy model distributions to interpret what they might resemble. <br/> Papers: [**Menon et al. 2021, MNRAS, 507,5542**](https://ui.adsabs.harvard.edu/abs/2021MNRAS.507.5542M/abstract)"
  url: /tpcf/
  btn_label: "Read More"
  btn_class: "btn--primary"
- image_path: /assets/images/HIFrag.png
  title: "The self-regulated formation of cold gas in the ISM via the thermal instability, shear and feedback."
  excerpt: "The star-forming dense, cold phase of in the ISM (i.e., the Cold Neutral Medium; CNM) forms and evolves amidst a combination of physical mechanisms operating at galactic scales: namely, the thermal instability, differential rotation/shear and stellar feedback. In my master's thesis, I performed numerical simulations with the *Athena* MHD code to explore how each of these mechanisms individually affects the formation and fragmentation of the CNM, and how the process of CNM formation and destruction is self-regulating over ~Gyr timescales <br/> [**Link to Master's Thesis**](https://www.dropbox.com/sh/afarzv6v6pvqyes/AACdRiKa9tuUTN-Z_GbyU1Qfa?dl=0)"
  url: "/hifrag/"
  btn_label: "Read More"
  btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row type="left" %} 






