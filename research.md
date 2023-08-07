---
title: ''
permalink: /research/
layout: post
comments: false
image: assets/img/badlands3.jpg

---

<p align="left"><em>My research blends the domains of atmospheric chemistry, air quality engineering, and machine learning/data science to uncover latent patterns in air pollution.</em></p>


<!-- # **Current Projects** -->

<!-- <font size="+1"><p align="center"><strong>Wildfire smoke, prescribed burns, and rural environmental justice in the western United States</strong></p></font> -->
# Wildfire smoke, prescribed burns, and rural environmental justice in the western United States
<figure>
<img src="/assets/img/west_fire.png" alt="controlled burns fig">
<figcaption><b>Contributions to population-weighted smoke exposure for the western United States in September 2020.</b> The figure shows the locations of MTBS prescribed burns (>1000 acres) during 2015-2020 (black dots, n=190) and the contribution of smoke PM2.5 emissions in each grid cell to population-weighted smoke exposure in the West receptor (colors). These contributions are calculated through multiplication of the GEOS‐Chem adjoint sensitivities of the West population‐weighted receptor by the GFED fire emissions for the month of September 2020.</figcaption>
</figure>

<br />

Catastrophic wildfires pose substantial risk to public health, infrastructures, and ecosystems in the western United States. As these large and costly wildfires become more common, methods to identify locations for prescribed burning are needed to mitigate impacts on affected populations and ecosystems. Here we investigate the effectiveness of prescribed burning for abating potential wildfire smoke exposures in states and rural environmental justice communities across the western United States during the destructive 2018 and 2020 fire seasons. We find that due in part to prevailing wind patterns, wildfires in the coastal states contribute more to overall smoke exposure in the West compared to wildfires in other states in both 2018 and 2020. We show that implementing prescribed burns in the heavily forested Northern California and the Pacific Northwest would yield large net benefits for the entire western United States, while doing so in other states would have relatively smaller impacts. Our work suggests that land managers should prioritize northern California, western Oregon, and eastern Washington for prescribed burns to mitigate future smoke exposure as these regions have a disproportionate impact on smoke exposure for rural environmental justice communities and population centers across the West.

**Publications**: [Kelp et al., (2023)](https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2022EF003468){:target="_blank"}

<br />


<!-- <font size="+1"><p align="center"><strong>Machine-learned atmospheric chemistry solver</strong></p></font> -->
# Machine-learned atmospheric chemistry solver
<figure>
<img src="/assets/img/onlineNN-min.png" alt="online NN fig">
<figcaption><b>ML chemical solver in GEOS-Chem.</b> GEOS-Chem computes the evolution of atmospheric composition by successive application over model time steps of components simulating advection, convection, emissions, planetary boundary layer (PBL) mixing, photolysis, chemistry, and deposition. We replace the 4th-order Rosenbrock solver with an ML solver that takes as input the same chemical concentrations and photolysis frequencies. All other model processes are the same as in the original model.</figcaption>
</figure>

<br />

Global models of atmospheric chemistry are computationally expensive. The chemical solver that integrates the large-dimensional coupled systems of kinetic equations describing the chemical mechanism is a bottleneck. Machine learning (ML) could be transformative for reducing the cost of an atmospheric chemistry simulation by replacing the chemical solver with a faster emulator. However, my past work found that ML chemical solvers experience rapid error growth and become unstable over time. My current work aims to achieve, for the first time, a stable full-year global simulation of atmospheric chemistry with three-month seasonal ML solvers. We show that online training of the ML solver synchronously with an atmospheric chemistry model simulation produces considerably more stable results than offline training from a static dataset of simulation results. Although our work represents an important step for using ML solvers in global atmospheric chemistry models, more work is needed to extend it to large chemical mechanisms and to reduce errors during long-term chemical aging.

**Publications**: [Kelp et al., (2022)](https://doi.org/10.1029/2021MS002926){:target="_blank"}, [Kelp et al., (2020)](https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1029/2020JD032759){:target="_blank"}, [Kelp et al., (2018) ArXiv](https://arxiv.org/abs/1808.03874){:target="_blank"}

<br />



<!-- <font size="+1"><p align="center"><strong>Optimal and equitable placement of PM<sub>2.5</sub> air quality sensors</strong></p></font> -->
# Optimal and equitable placement of PM<sub>2.5</sub> air quality monitors

<figure>
<img src="/assets/img/EJsensors2.jpg" alt="sensors fig">
<figcaption><b>PM<sub>2.5</sub> locations for St. Louis and Houston.</b> Distribution of sensor locations identified as optimal by the  multiresolution dynamic mode decomposition (mrDMD) algorithm, and those identified as optimal and equitable by the cost-constrained mrDMD (mrDMDcc) using race and income metrics. All sensor locations are gridded onto a 1 km x 1 km grid. Dots represent sensor locations with the shading representing the proportion of nonwhite (left and center columns) or low-income households (right column) in that grid box. Dots outlined in red indicate areas with historic environmental justice issues mentioned in the main text – for example Granite City, IL, and East St. Louis, IL, for the race optimized mrDMDcc case.
</figcaption>
</figure>

<br />

In the United States, citizens and policymakers rely upon Environmental Protection Agency (EPA) mandated regulatory networks to monitor air pollution; increasingly, low-cost sensor networks supplement spatial gaps in the regulatory monitor networks. Although these regulatory and low-cost networks provide enhanced spatiotemporal coverage in urban areas, sensors are located most often in higher income, predominantly White areas. Here we use a modal decomposition algorithm to identify the optimal and equitable placement of fine particulate matter (PM<sub>2.5</sub>) sensors in four U.S. cities with histories of racial or income segregation: St. Louis, Houston, Boston, and Buffalo. Compared to networks using air pollution information alone, the algorithm places a greater number of sensors in historically low-income and nonwhite neighborhoods with known environmental pollution problems, while also capturing PM<sub>2.5</sub> extremes. Our work provides a roadmap for the creation of equitable sensor networks in U.S. cities and offers a guide for democratizing air pollution data by increasing spatial coverage of low-cost sensors in less privileged communities.

**Publication**: [Kelp et al., preprint](https://eartharxiv.org/repository/view/5099/){:target="_blank"}, [Kelp et al., (2022)](https://iopscience.iop.org/article/10.1088/1748-9326/ac548f){:target="_blank"}

<br />


# **Past Projects**


<!-- <font size="+1"><p align="center"><strong>Vehicle emission factors for area-wide mobile monitoring</strong></p></font> -->
# Vehicle emission factors for area-wide mobile monitoring

<figure>
<img src="/assets/img/LA_roads_fig.png" alt="LA fig">
<figcaption><b>Road and street classifications in Los Angeles County with county base map provided by the U.S.</b> Census Bureau's Master Address File / Topologically Integrated Geographic Encoding and Referencing (MAF/TIGER) Database (MTDB). (src credit: Yurika Harada).</figcaption>
</figure>

<br />

On-road vehicle emissions are a significant source of outdoor air pollution, which pose a severe human health risk, especially for those who live near busy roads. A city's vehicle fleet can determine the levels of risk and exposure for residences as emissions differ for gasoline- vs. diesel-powered vehicles. Most research sampling mobile source emissions in urban traffic involves “vehicle chase” studies of exhaust plumes from individual vehicles which may not be representative of the average emissions for a given area.

We create a statistical model from measurements obtained from continuously moving platforms to estimate area-wide average vehicle emission factors of neighborhoods. These model predictions are used to estimate emission factors by source-related features within a city. Furthermore, our model can calculate separately light-duty and heavy-duty vehicle emission factors for a study area while also separating out high-emitter vehicles that may artificially skew emission factor estimates. Study areas include Los Angeles, USA and Chengdu, China.

**Publications**: [Kelp et al., (2020)](https://www.sciencedirect.com/science/article/pii/S1352231019308519){:target="_blank"}, [Wen et al., (2019)](https://www.sciencedirect.com/science/article/pii/S0048969719317140){:target="_blank"}

<br />

<!-- <font size="+1"><p align="center"><strong>Indoor air pollution from cookstove intervention in rural South India</strong></p></font> -->
# Indoor air pollution from cookstove intervention in rural South India

<figure>
<img src="/assets/img/cookstove_fig.jpg" alt="cookstove fig" width="400">
<figcaption>
Diurnal distribution of real-time PM<sub>2.5</sub> concentrations with 10 min resolution. “S1” (A) is the pre-intervention baseline and “S2” (B) is the post-intervention follow-up.
</figcaption>
</figure>

<br />

Biomass combustion from residential cookstoves is a major source of indoor air pollution and a large contributor to the global burden of disease. Investment of resources into rural energy intervention programs has great potential to improve household air quality in developing countries and thus increase quality of life and improve public health. We conducted a randomized intervention study to evaluate air pollution impacts of a carbon-finance-approved cookstove in rural South India. We employed real-time monitors to measure indoor concentrations of PM<sub>2.5</sub>, black carbon (BC) and carbon monoxide (CO) in households using carbon-finance-approved stoves and households continuing to use traditional open fire stoves. Implementation of the new cookstoves decreased concentrations of CO and PM<sub>2.5</sub>, but increased BC concentrations relative to the traditional stoves.

Although lab studies have clearly demonstrated the potential benefits of cookstove interventions, achieving these same benefits in real households is more complex. This work suggests that reduction in indoor pollution from intervention cookstoves might not be occurring in practice to the same extent as is expected from lab evaluation, and that benefits from such interventions should not be assumed.

**Publication**: [Kelp et al., (2018)](https://www.sciencedirect.com/science/article/pii/S2352728517300726){:target="_blank"}

<br />

<!-- <font size="+1"><p align="center"><strong>Actionable sampling: Heavy metals air quality monitoring in Portland, OR</strong></p></font> -->
# Heavy metals air quality monitoring in Portland, OR

<figure>
<img src="/assets/img/arsenic_monitoring.png" alt="train fig">
</figure>

<br />

Teaming up with the Oregon Department of Environmental Quality (DEQ), I was an air quality sample assistant during the fall of 2015. I helped install and collect BGI filters and maintained an EPA-validated method sampling site. We created [statewide attention](https://www.portlandmercury.com/BlogtownPDX/archives/2016/02/03/arsenic-cadmium-levels-near-two-se-portland-schools-are-alarmingly-high-state-finds) to elevated arsenic and cadmium concentrations near two schools (including a kindergarten) in SE Portland. We identified the source of the heavy metal pollution as coming from the Bullseye Glass Co. which then [suspended its use of chromium](https://www.portlandmercury.com/BlogtownPDX/archives/2016/02/04/bullseye-glass-has-suspended-use-of-arsenic-and-cadmium-because-of-air-quality-concerns) in its products. Our monitoring efforts helped lead to the Cleaner Air Oregon regulations written by DEQ and the Oregon Health Authority, and are supported by Governor Kate Brown.

**Publication**: [EPA-DEQ certification](https://drive.google.com/file/d/1MBypsl_yBFwdpMGOHG97ZG_KQ9k5zbXS/view)

<br />

<!-- <font size="+1"><p align="center"><strong>Measuring coal dust from trains in the Columbia River Gorge, WA</strong></p></font> -->
# Measuring coal dust from trains in the Columbia River Gorge, WA

<figure>
<img src="/assets/img/gorge_fig.png" alt="train fig">
<figcaption> Images captured from the video camera before and after coal train passage on 8/7/2014 at 17:28 PDT.</figcaption>
</figure>

<br />

Trains powered by diesel fuel travel through the Columbia River Gorge as well as many urban areas in Washington State. Evaluating the air quality impacts from rail traffic on people living near rail lines is hampered by a lack of monitoring data. Emission standards for new and remanufactured locomotives have decreased steadily over the past several decades. Because of the lack of information on PM<sub>2.5</sub> exposure to humans from diesel trains, we sought to measure these air quality effects.

During summer 2014, we monitored emissions of diesel PM<sub>2.5</sub> and coal dust from trains in the Columbia River Gorge and found that the transit of diesel powered open-top coal trains result in nearly twice as much respirable PM<sub>2.5</sub> compared to the passage of diesel-powered freight trains not carrying coal. Furthermore, we witnessed multiple “super-duster” events during which the coal dust emissions led to visible dust plumes and the highest PM<sub>2.5</sub> concentrations observed in our study.

**Publication**: [Jaffe et al., (2015)](https://www.sciencedirect.com/science/article/abs/pii/S1309104215000057){:target="_blank"}
