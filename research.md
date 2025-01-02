---
title: ''
permalink: /research/
layout: post
comments: false
image: assets/img/badlands3.jpg
class: research-page

---

<div class="research-page">

<font size="+3">Research Interests</font>

<p>
My work centers on advancing the understanding of atmospheric chemistry and its intersections with human and environmental systems. I am particularly interested in <em>leveraging innovative data science and machine learning techniques to address complex challenges in air quality and wildfire land/smoke management.</em> I enjoy approaching problems from unique perspectives, uncovering insights through the exploration of unconventional methods and data sources.
</p>

<br />

<font size="+3">Current Research Areas</font>
<br />

<font size="+2"><p align="center">Wildfire, Prescribed Fire Smoke Modeling and Mitigation</p></font>

<figure style="border: 2px solid #000; padding: 10px; border-radius: 5px;">
  <img src="/assets/img/west_fire.png" alt="controlled burns fig">
  <figcaption>Wildfire emissions contributing to population-weighted smoke exposures across the western United States in September 2020 (Kelp et al., 2023).</figcaption>
</figure>

<div style="height: 20px;"></div>

<p>
Catastrophic wildfires pose substantial risks to public health, infrastructures, and ecosystems in the western United States. As these large and costly wildfires become more common, methods to identify locations for prescribed burning are needed to mitigate impacts on affected populations and ecosystems. Here we investigate the effectiveness of prescribed burning for abating potential wildfire smoke exposures in states and rural environmental justice communities across the western United States during the destructive 2018 and 2020 fire seasons. We find that, due in part to prevailing wind patterns, wildfires in the coastal states contribute more to overall smoke exposure in the West compared to wildfires in other states in both 2018 and 2020. We show that implementing prescribed burns in the heavily forested Northern California and the Pacific Northwest would yield large net benefits for the entire western United States, while doing so in other states would have relatively smaller impacts. Our work suggests that land managers should prioritize northern California, western Oregon, and eastern Washington for prescribed burns to mitigate future smoke exposure as these regions have a disproportionate impact on smoke exposure for rural environmental justice communities and population centers across the West.
</p>

<p>
<strong>Publications:</strong> <a href="https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2022EF003468" target="_blank">Kelp et al., (2023)</a>
</p>
<p>
<strong>Co-Authored Wildfire Publications:</strong> <a href="https://pubs.acs.org/doi/10.1021/acs.est.4c05922" target="_blank">Qiu et al., in-press (2024)</a>, <a href="https://www.publish.csiro.au/WF/WF23148" target="_blank">Liu et al., (2024)</a>
</p>

<br />

<font size="+2"><p align="center">Deep Learning Atmospheric Chemistry</p></font>

<figure style="border: 2px solid #000; padding: 10px; border-radius: 5px;">
  <img src="/assets/img/onlineNN-min.png" alt="online NN fig">
  <figcaption>Machine-learned chemical solver embedded in the 3-D chemical transport model GEOS-Chem (Kelp et al., 2022).</figcaption>
</figure>

<div style="height: 20px;"></div>

<p>
Global models of atmospheric chemistry are computationally expensive. The chemical solver that integrates the large-dimensional coupled systems of kinetic equations describing the chemical mechanism is a bottleneck. Machine learning (ML) could be transformative for reducing the cost of an atmospheric chemistry simulation by replacing the chemical solver with a faster emulator. However, my past work found that ML chemical solvers experience rapid error growth and become unstable over time. My current work aims to achieve, for the first time, a stable full-year global simulation of atmospheric chemistry with three-month seasonal ML solvers. We show that online training of the ML solver synchronously with an atmospheric chemistry model simulation produces considerably more stable results than offline training from a static dataset of simulation results. Although our work represents an important step for using ML solvers in global atmospheric chemistry models, more work is needed to extend it to large chemical mechanisms and to reduce errors during long-term chemical aging.
</p>

<p>
<strong>Publications:</strong> <a href="https://doi.org/10.1029/2021MS002926" target="_blank">Kelp et al., (2022)</a>, <a href="https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1029/2020JD032759" target="_blank">Kelp et al., (2020)</a>, <a href="https://arxiv.org/abs/1808.03874" target="_blank">Kelp et al., (2018)</a>
</p>
<p>
<strong>Co-Authored ML Publications:</strong> <a href="https://amt.copernicus.org/articles/16/3787/2023/" target="_blank">Balasus et al., (2023)</a>
</p>

<br />

<font size="+2"><p align="center">Data-Driven Air Pollution Sensing</p></font>

<figure style="border: 2px solid #000; padding: 10px; border-radius: 5px;">
  <img src="/assets/img/EJsensors2.jpg" alt="sensors fig">
  <figcaption>Distribution of PM<sub>2.5</sub> sensor locations in St. Louis, MO, and Houston, TX identified as optimal by the multiresolution Dynamic Mode Decomposition (mrDMD) (Kelp et al., 2023).</figcaption>
</figure>

<div style="height: 20px;"></div>

<p>
In the United States, citizens and policymakers rely upon Environmental Protection Agency (EPA) mandated regulatory networks to monitor air pollution; increasingly, low-cost sensor networks supplement spatial gaps in the regulatory monitor networks. Although these regulatory and low-cost networks provide enhanced spatiotemporal coverage in urban areas, sensors are located most often in higher income, predominantly White areas. Here we use a modal decomposition algorithm to identify the optimal and equitable placement of fine particulate matter (PM<sub>2.5</sub>) sensors in four U.S. cities with histories of racial or income segregation: St. Louis, Houston, Boston, and Buffalo. Compared to networks using air pollution information alone, the algorithm places a greater number of sensors in historically low-income and nonwhite neighborhoods with known environmental pollution problems, while also capturing PM<sub>2.5</sub> extremes. Our work provides a roadmap for the creation of equitable sensor networks in U.S. cities and offers a guide for democratizing air pollution data by increasing spatial coverage of low-cost sensors in less privileged communities.
</p>

<p>
<strong>Publications:</strong> <a href="https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2023GH000834" target="_blank">Kelp et al., (2023)</a>, <a href="https://iopscience.iop.org/article/10.1088/1748-9326/ac548f" target="_blank">Kelp et al., (2022)</a>
</p>
<p>
<strong>Co-Authored Sensor/EJ Publications:</strong> <a href="https://eartharxiv.org/repository/view/6911/" target="_blank">Kawano et al., (preprint, in-press)</a>, <a href="https://pubs.acs.org/doi/10.1021/acs.est.1c07005" target="_blank">Yang et al., (2022)</a>
</p>

<br />
</div>
