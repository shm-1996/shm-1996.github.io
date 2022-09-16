---
title: "The role of radiatino pressure in star cluster formation"
permalink: /radpressure/
author_profile: True
layout: splash
classes: wide
gallery:
  - url: /assets/images/Rad_CompareSFEMW.pdf
    image_path: /assets/images/Rad_CompareSFEMW.pdf
    alt: "Scuba diving."
    title: "Scuba diving in Jervis Bay, New South Wales. Photo credits: "
  - url: /assets/images/Rad_CompareSFEMW.pdf
    image_path: /assets/images/Rad_Opac.pdf
    alt: "placeholder image 2"
    title: "Image 2 title caption"
  - url: /assets/images/Rad_CompareSFEMW.pdf
    image_path: /assets/images/Rad_RadMatter.pdf
    alt: "placeholder image 3"
    title: "Image 3 title caption"
---
<h3><u>
  Radiation Pressure in Regulating Star Formation and Driving Winds in Star Clusters
</u> </h3>

Radiation pressure on dust grains is an important feedback mechanism in the ISM. In star-forming regions, dust grains absorb the energy and momentum in ultraviolet (UV) photons from massive stars, and via collisions with gas particles impart this energy and momentum to the gas. The energy input can heat the gas and supress fragmentation, and the radiation pressure can act as a support against gravitational collapse, and possibly drive outflows if sufficiently strong. In addition, dust grains re-emit the absorbed energy at infrared (IR) wavelengths, which, in extreme environments such as super-star cluster forming environments in starbursts (e.g. NGC 253), can be optically thick and itself provide momentum support to the star-forming cloud -- sometimes significantly greater than that available in the UV photons. 

In [Menon, Federrath & Krumholz 2022a](https://ui.adsabs.harvard.edu/abs/2022arXiv220614190M/abstract), we tested the role of the momentum available in the dust-reprocessed IR photons in regulating star formation in super-star cluster forming environments with our recently developed novel radiation hydrodynamics scheme [VETTAM](https://ui.adsabs.harvard.edu/abs/2022MNRAS.512..401M/abstract). We found that the radiation pressure from IR photons is unable to provide support against gravitional collapse, unlike the predictions of some semi-analytic models. This is primarily due to the fact that the dust opacities in the IR are not sufficiently high for radiation forces to compete against gravity, even in extremely dense conditions. It is only in conditions where the dust abundances are higher (~ 3 times the solar value) and/or the IMF is top-heavy that IR radiation pressure can play a dynamical role in star cluster formation, and even there the escape of radiation through optically thin channels lowers the efficiency of the mechanism. 

{% include gallery caption="Radiation pressure due to dust-reprocessed IR photons are unable to regulate the star formation efficiency in clusters (left): A control run without radiation (No RT) has identical SFE to those with radiation; only at dust-to-gas ratios ~ 3 is there some effect, even then a marginal one. The reason for this behaviour is that the IR opacities are too low to counteract the gravitational forces; some semi-analytic models/simulations in the past have used a power-law/constant approximation for the dust opacities which overestimates the opacities and the effectiveness of feedback (Middle plot). Even if dust opacities are higher due a higher D/G ratio, radiation tends to escape through low-density channels, largely counteracting the increased potential for feedback (Right). " %}

<!-- ![image-left](/assets/images/UVIRDensity.pdf){: .align-left} -->
<figure style="width: 30%" class="align-left">
  <a href="/assets/images/UVIRDensity.pdf" title="Projected gas density" alt="Projected gas density">
  <img src="/assets/images/UVIRDensity.pdf" alt=""></a>
  <figcaption>Projected gas density with gas velocities denoted with vectors, showing outflowing gas driven by UV and IR radiation pressure.</figcaption>
</figure>


However, in Menon, Federrath & Krumholz 2022b (in prep), we tested simulations with both the radiation pressure in the UV and IR bands. The former could be important in the less extreme surface density clouds we modelled in the first paper; especially because the opacity for dust grains in the UV is significantly higher than in the IR. Our simulations find that even with the UV radiation pressure, star formation proceeds unregulated for $\Sigma$>3.2e5. However, radiation pressure is able to drive winds in some regions of parameter space after achieving high SFE's which go on to escape the cloud; this wind have mass-weighted velocities from 15-30 km/s, although they do not carry significant mass. This range of surface densities are comparable to those of young super-star clusters found in starburst galaxies. Therefore radiation pressure could possibly explain recent observations of high-velocity neutral gas outflows from super-star clusters (e.g. Levy et al. 2021). 

<figure style="width: 30%" class="align-right">
  <a href="/assets/images/CumForceRatio.pdf" title="UV/IR Momentum contribution" alt="UV/IR Momentum contribution">
  <img src="/assets/images/CumForceRatio.pdf" alt=""></a>
  <figcaption>Cumulative radial momentum imparted on gas by photons in our simulations (UV+IR), also split by the individual contributions by UV and IR photons, in units of the maximum available momentum in UV photons. </figcaption>
</figure>

<!-- ![image-right](/assets/images/CumForceRatio.pdf){: .align-right} Caption of image -->

Interestingly, we found that both UV and IR radiation pressures are important for this behaviour in this region of parameter space, and their cumulative momentum contributions comparable. This is quantified in the plot on the right, where we quantify the cumulative momentum imparted by photons in the UV and IR bands; we can see that for Sigma ~ 13 - 104, the UV and IR radiation pressures are comparable, whereas for values above (below) this range the IR (UV) radiation pressure dominates the feedback budget. In terms of driving the outflows, we found that the impulse provided by the UV radiation pressure launches the outflows, with the role of the IR component primarily to entrain a larger fraction of gas in the outflows.

<a href="https://ui.adsabs.harvard.edu/abs/2022arXiv220614190M/abstract" class="btn btn--primary">Menon, Federrath & Krumholz 2022a</a> <a href="#" class="btn btn--primary">Menon, Federrath & Krumholz 2022b</a> <a href="/radpres_movies" class="btn btn--primary">Simulation Movies</a>  
