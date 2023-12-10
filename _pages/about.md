---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---
I am a passionate physicist with expertise in climate modeling of hot gas giant exoplanets. (Soon) PhD holder in astrophysics and master's degree in physics. Experienced in emulating algorithms with machine learning and translating complex physical concepts into code. I am first author of six refereed publications and coauthor to several more. Seeking new opportunities and soon relocating to the Stuttgart region.

I am a Marie Sklodowska-Curie early stage researcher in astronomy and astrophysics in the [CHAMELEON](https://chameleon.iwf.oeaw.ac.at/ "CHAMELEON")<sup>1</sup> network, focusing on connecting the atmosphere and interior of extrasolar gas planets. From 2021 to 2022, I spent 18 months in Leuven, Belgium, collaborating with Leen Decin and Ludmila Carone. From March 2022 to the end of 2023, I completed the second half of my PhD in København, Denmark, working with Uffe Gråe Jørgensen.

Planetformation
======
During my master thesis, I developed a global planet formation code [(chemcomp)](https://chemcomp.readthedocs.io/ "chemcomp"), capable of modeling the formation of planets in viscously evolving disks (including drift and evaporation of pebbles), while tracing their chemical composition of the forming planets. The [chemcomp](https://chemcomp.readthedocs.io/ "chemcomp") code [(Schneider & Bitsch 2021)](https://ui.adsabs.harvard.edu/abs/2021A&A...654A..71S "Link to Publication"), which has now been used in 11 publications, is now also publically available!

<img src="images/water_in_pla_mig.png" alt="Water content of planets formed in chemcomp" width="100%"/>

Planetary atmospheres
======
During my PhD, I integrated an precise and efficient radiative transfer solver with a general circulation model (GCM) to investigate the relationship between Hot Jupiter radius inflation and atmospheric dynamics. Hot Jupiters are gas giant planets that are heavily exposed to radiation and have winds reaching a few km/s. A comprehensive understanding of these planets necessitates the use of consistent 3D radiative hydrodynamic modeling.

<img src="images/zonal_mean_WASP-43b.png" alt="Zonal Mean of WASP-43b" width="33%"/>
<img src="images/temp_WASP-43b.png" alt="temperature Maps of WASP-43b" width="66%"/>

Furthermore, I benchmarked various statistical opacity approximations and developed a machine learning algorithm to effectively address the computational problem of overlapping molecular species in gas radiative transfer. The DeepSet mixing algorithm that I developed is both efficient and accurate and easy to couple to radiative hydrodynamic models. Read more about it in the publication ([Schneider et al. 2023](https://ui.adsabs.harvard.edu/abs/2023arXiv231100775S)) or read about the code (its open source!): [opacmixer](https://github.com/AaronDavidSchneider/opacmixer, "Link to Publication"). 

<img src="images/DS.jpeg" alt="DeepSet mixing of opacity species" width="50%"/>

Software development
======
I am a passionate software developer with experience in developing various codes professionally and privately. I utilize modern tools like Github actions to ensure the functionality of my code.Furthermore, in my spare time I occasionally contribute to [homeassistant](https://www.home-assistant.io "homeassistant") and the components [SonosAlarm](https://github.com/AaronDavidSchneider/SonosAlarm "SonosAlarm") and [FRITZ!Box Tools](https://github.com/mammuth/ha-fritzbox-tools "FRITZ!Box Tools") or work on extensions for [raycast](https://www.raycast.com/), such as [bibmanager](https://www.raycast.com/aaronschneider/bibmanager).

<a href="https://chameleon.wp.st-andrews.ac.uk"><img src="images/Chameleon.jpg" alt="CHAMELEON" width="15%"/></a>
<a href="https://ec.europa.eu/"><img src="images/EU.jpg" alt="EU" width="15%"/></a>
<a href="https://ec.europa.eu/research/mariecurieactions/msca-actions_en"><img src="images/MSCA.png" alt="MSCA" width="15%"/></a>
<a href="https://www.mpia.de"><img src="images/MPIA.jpg" alt="MPIA" width="15%" height="100"/></a>
<a href="https://www.ku.dk"><img src="images/UCPH.jpg" alt="UCPH" width="15%"/></a>
<a href="https://www.kuleuven.be/kuleuven/"><img src="images/KULeuven.png" alt="KULeuven" width="15%"/></a>

<p class="text-muted"><small>[1] This project has received funding from the European Union’s Horizon 2020 research and innovation programme under the Marie Sklodowska-Curie grant agreement No 860470.</small></p>
