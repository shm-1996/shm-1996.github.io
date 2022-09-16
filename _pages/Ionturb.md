---
title: "Radiation feedback and the turbulent ISM"
permalink: /ionturb/
author_profile: True
layout: splash
classes: wide
---
<h3><u>
	Interplay of Turbulence and Feedback in the ISM 
</u> </h3>

The radiation emitted by massive stars, and the energy and momentum they impart on the gas surrounding them, can have significant effects on their dynamics. The primary role of feedback is to clear and disperse gas in star-forming clouds, and thereby maintain a low efficiency of star formation. However, while this is occuring, the feedback also shapes this gas, and the resulting turbulent density and velocity structure. In [**Menon, Federrath & Kuiper 2020**](https://ui.adsabs.harvard.edu/abs/2020MNRAS.493.4643M/abstract) we set out to probe this role played by feedback by running idealised RHD simulations with the *PLUTO* code. We setup an initially turbulent cloud, and introduced a temporally-constant plane-parallel front of ionizing radiation on this gas (see movie below). This patch of gas could be thought of as a section of an expanding HII region, and the impinging radiation field as that incoming from the massive star/cluster driving the expansion. The radiation field then ionizes the gas in the turbulent cloud, and the increased thermal pressure of the ionized gas pushes the gas outward (towards the right) and also compresses and shapes the gas to produce pillar-like structures, reminiscent of the famous [*Pillars of Creation*](https://www.nasa.gov/image-feature/the-pillars-of-creation/) . The movie below shows the line-of-sight column density of the gas perpendicular (left) and parallel (right) to the direction of the incoming radiation front.

<video muted autoplay controls width="95%" controls="controls">
  <source src="/assets/videos/UVTurbulence.mp4" type="video/mp4">
</video>


<figure style="width: 45%" class="align-right">
  <a href="/assets/images/Pillar_bvalues.pdf" title="Pillar b values" alt="Pillar b values">
  <img src="/assets/images/Pillar_bvalues.pdf" alt=""></a>
  <figcaption>Turbulence driving parameter measured in our numerical simulations as a function of time for all the neutral gas in the medium measured through two independent methods (red and blue) both of which denote compressive turbulence.</figcaption>
</figure>

\\
We found from our simulations that the ionizing radiation drives compressive turbulent motions in these pillar-like gas structures, increasing the relative availablility of dense gas. This compressive nature of the gas is quantified through the so-called turbulence driving parameter (*b*), which quantifies the extent to which turbulence in a region is solenoidal (vortex-like, stirring motions) or compressive (which produces shocks). We found a value of *b* that indicates strongly compressive turbulence (see Figure). This has consequences for the future star formation in such regions; strong compressive turbulence has been shown to increase the star formation rate in an environment (see, e.g. [Federrath & Klessen 2012](https://ui.adsabs.harvard.edu/abs/2012ApJ...761..156F/abstract)). This could possibly suggest that the ionizing radiation could trigger star formation in this gas through the mechanism of driving compressive turbulence. Please see [**Menon, Federrath & Kuiper 2020**](https://ui.adsabs.harvard.edu/abs/2020MNRAS.493.4643M/abstract) for further details. Additional studies with more physical mechanisms (e.g. magnetic fields), and a more direct estimate of star formation rates would help shed light on the plausibility of triggering. 
 

Following on this result, we set out to test this idea with observations in [**Menon et al. 2021a**](https://ui.adsabs.harvard.edu/abs/2021MNRAS.500.1721M/abstract), in collaboration with [Pamela Klaassen](https://www.roe.ac.uk/~pk/). We used high-resolution observations of six pillar-like regions in the Carina nebula, observed with the [Atacama Large Millimeter/submillimeter Array (ALMA)](https://www.almaobservatory.org/en/home/) telescope. We combined information from the rotational lines of three isotopologues of CO to infer the (projected) density and line-of-sight velocity structure, and with them, produced an *observational estimate of the driving parameter*. We found excellent pretty good agreement (on average) in the values of *b* we measured in the observations with that predicted from our simulations.

<figure style="width: 40%" class="align-left">
  <a href="/assets/images/CarinaPillar.pdf" title="Pillar 20" alt="Pillar 20">
  <img src="/assets/images/CarinaPillar.pdf" alt=""></a>
  <figcaption> Column density map of one of the pillars of the Carina nebula we probed.</figcaption>
</figure>

<figure style="width: 50%" class="align-right">
  <a href="/assets/images/bSimObsCompare.pdf" title="Pillar 20" alt="Pillar 20">
  <img src="/assets/images/bSimObsCompare.pdf" alt=""></a>
  <figcaption> Driving parameter for the six different pillar regions we probed (M21) in Carina (denoted by their IDs) and the value obtained from our numerical simulations (M20; dashed lines). Dotted purple lines denote a natural mixture of solenoidal and compressive modes, and denotes the transition point from which turbulence is increasingly solenoidal or compressive dominated (annotated).</figcaption>
</figure>
