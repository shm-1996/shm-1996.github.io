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

In Menon, Federrath & Krumholz 2022a, we tested the role of the momentum available in the dust-reprocessed IR photons in regulating star formation in super-star cluster forming environments with our recently developed novel radiation hydrodynamics scheme VETTAM (see below). We found that the radiation pressure from IR photons is unable to provide support against gravitional collapse, unlike the predictions of some semi-analytic models. This is primarily due to the fact that the dust opacities in the IR are not sufficiently high for radiation forces to compete against gravity, even in extremely dense conditions. It is only in conditions where the dust abundances are higher (~ 3 times the solar value) and/or the IMF is top-heavy that IR radiation pressure can play a dynamical role in star cluster formation, and even there the escape of radiation through optically thin channels lowers the efficiency of the mechanism. 

{% include gallery caption="Radiation pressure due to dust-reprocessed IR photons are unable to regulate the star formation efficiency in clusters (left): A control run without radiation (No RT) has identical SFE to those with radiation; only at dust-to-gas ratios ~ 3 is there some effect, even then a marginal one. The reason for this behaviour is that the IR opacities are too low to counteract the gravitational forces; some semi-analytic models/simulations in the past have used a power-law approximation for the dust opacities which would not show this behaviour (Middle plot). Even if dust opacities are higher due a higher D/G ratio, radiation tends to escape through low-density channels, largely counteracting the increased potential for feedback (Right). " %}

However, in Menon, Federrath & Krumholz 2022b, we tested simulations with both the radiation pressure in the UV and IR bands. The former could be important in the less extreme surface density clouds we modelled in the first paper; especially because the opacity for dust grains in the UV is significantly higher than in the IR. Our simulations find that even with the UV radiation pressure, star formation proceeds unregulated for Sigma>3.2e5. However, radiation pressure is able to drive winds in some regions of parameter space after achieving high SFE's which go on to escape the cloud; this wind could have velocities from 50-100 km/s, although they do not carry significant mass. This range of surface densities are comparable to those of young super-star clusters found in starburst galaxies. Therefore radiation pressure could possibly explain recent observations of high-velocity neutral gas outflows from super-star clusters. 

Interestingly, we found that both UV and IR radiation pressures are important for this behaviour in this region of parameter space, and their cumulative momentum contributions comparable. This is quantified in the plot below; we can see that for Sigma ~ 13 - 104, the UV and IR radiation pressures are comparable over the extent of the cloud; on the other hand, for values above (below) this range the IR (UV) radiation pressure dominates the feedback budget. Combining the finding from Menon, Federrath & Krumholz 2022a that the IR radiation pressure is unable to dynamically impact the gas, this implies that clouds evolve mostly unaffected by feedback in very high surface density clouds. 
