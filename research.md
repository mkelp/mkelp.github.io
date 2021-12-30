---
title: ''
permalink: /research/
layout: post
comments: false
image: assets/img/badlands3.jpg

---

<p align="left"><em>My research blends the domains of atmospheric chemistry, air quality engineering, and machine learning/data science to discover latent patterns in air pollution</em></p>


# **Current Projects**

<font size="+1"><p align="center"><strong>Machine-learned atmospheric chemistry solver</strong></p></font>

<figure>
<img src="/assets/img/onlineNN.png" alt="online NN fig">
<figcaption>Simulation of surface ozone by different ML solvers implemented within GEOS-Chem. The left and middle panels show absolute and fractional errors at the end of a 31-day July 2017 simulation relative to the reference simulation using the standard GEOS-Chem solver. The right panel shows the temporal evolution of the global hourly root-mean-square error (RMSE) over the 31-day period. The mean RMSE for the last 10 days of July is given inset.</figcaption>
</figure>

<br />

Global models of atmospheric chemistry are computationally expensive. A bottleneck is the chemical solver that integrates the large-dimensional coupled systems of kinetic equations describing the chemical mechanism. Machine learning (ML) could be transformative for reducing the cost of an atmospheric chemistry simulation by replacing the chemical solver with a faster emulator. However, my past work found that ML chemical solvers experience rapid error growth and become unstable over time. My current work aims to achieve for the first time a stable full-year global simulation of atmospheric chemistry with a ML solver. We show that online training of the ML solver synchronously with an atmospheric chemistry model simulation produces considerably more stable results than offline training it from a static dataset of simulation results. Although our work represents an important step for using ML solvers in global atmospheric chemistry models, more work is needed to extend it to large chemical mechanisms and to reduce errors during long-term chemical aging.

**Publications**: [Kelp et al., *submitted to JAMES*](https://eartharxiv.org/repository/view/2886/){:target="_blank"}, [Kelp et al., (2020)](https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1029/2020JD032759){:target="_blank"}, [Kelp et al., (2018) ArXiv](https://arxiv.org/abs/1808.03874){:target="_blank"}

<br />

<font size="+1"><p align="center"><strong>Optimal placement of PM<sub>2.5</sub> air quality sensors</strong></p></font>

<figure>
<img src="/assets/img/west_sensors.jpg" alt="sensors fig">
<figcaption>PM<sub>2.5</sub> sensor locations in the West. Comparison of sensor locations for the EPA
monitoring network and the mrDMD algorithm. Small grey patches in the Southwest and Pacific Northwest reflect grid cells with missing or corrupted data that were discarded from this analysis.</figcaption>
</figure>

<br />

Considerable financial resources are allocated for measuring ambient air pollution in the United States, yet the locations for these monitoring sites may not be optimized to capture the full extent of current pollution variability. Prior research on best sensor placement for monitoring fine particulate matter (PM<sub>2.5</sub>) pollution is scarce: most studies do not span areas larger than a medium-sized city or examine timescales longer than one week. Here we present a pilot study using multiresolution modal decomposition (mrDMD) to identify the optimal placement of PM<sub>2.5</sub> sensors from 2000-2016 over the contiguous United States. This novel approach incorporates the variation of PM<sub>2.5</sub> on timescales ranging from one day to over a decade to capture air pollution variability. We find that the mrDMD algorithm identifies high-priority sensor locations in the western United States, but a significantly lower density of sensors than expected along the eastern coast, where a large number of EPA PM<sub>2.5</sub> monitors currently reside. Specifically, 53% of mrDMD optimized sensor locations are west of the 100th meridian, compared to only 32% in the current EPA network. The mrDMD sensor locations can capture PM<sub>2.5</sub> from wildfires and high pollution events, with particularly high skill in the West. These results suggest significant gaps in the current EPA monitoring network in the San Joaquin Valley in California, northern California, and in the Pacific Northwest (Idaho, and Eastern Washington and Oregon). Our framework diagnoses where to place air quality sensors so that they can best monitor smoke from wildfires. Our framework may also be applied to urban areas for equitable placement of PM<sub>2.5</sub> monitors.



**Publication**: [Kelp et al., *submitted to Env. Res. Let.*](){:target="_blank"}

<br />

# **Past Projects**


<font size="+1"><p align="center"><strong>Vehicle emission factors for area-wide mobile monitoring</strong></p></font>

<figure>
<img src="/assets/img/LA_roads_fig.png" alt="LA fig">
<figcaption>Road and street classifications in Los Angeles County with county base map provided by the U.S. Census Bureau's Master Address File / Topologically Integrated Geographic Encoding and Referencing (MAF/TIGER) Database (MTDB). (src credit: Yurika Harada).</figcaption>
</figure>

<br />

On-road vehicle emissions are a significant source of outdoor air pollution which pose a severe human health risk, especially for those who live near busy roads. A city's vehicle fleet can determine the levels of risk and exposure for residences as emissions differ for gasoline- vs. diesel-powered vehicles. Most research sampling mobile source emissions in urban traffic involve “vehicle chase” studies of exhaust plumes from individual vehicles which may not be representative of the average emissions for a given area.

We create a statistical model from measurements obtained from continuously moving platforms to estimate area-wide average vehicle emission factors of neighborhoods. These model predictions are used to estimate emission factors by source-related features within a city. Furthermore, our model can calculate separately light-duty and heavy-duty vehicle emission factors for a study area while also separating out high-emitter vehicles that may artificially skew emission factor estimates. Study areas include Los Angeles, USA and Chengdu, China.

**Publications**: [Kelp et al., (2020)](https://www.sciencedirect.com/science/article/pii/S1352231019308519){:target="_blank"}, [Wen et al., (2019)](https://www.sciencedirect.com/science/article/pii/S0048969719317140){:target="_blank"}

<br />

<font size="+1"><p align="center"><strong>Indoor air pollution from cookstove intervention in rural South India</strong></p></font>

<figure>
<img src="/assets/img/cookstove_fig.jpg" alt="cookstove fig" width="400">
<figcaption>
Diurnal distribution of real-time PM<sub>2.5</sub> concentrations with 10 min resolution. “S1” (A) is the pre-intervention baseline and “S2” (B) is the post-intervention follow-up.
</figcaption>
</figure>

<br />

Biomass combustion from residential cookstoves is a major source of indoor air pollution and a large contributor to the global burden of disease. Investment of resources into rural energy intervention programs has great potential to improve household air quality in developing countries and thus increase quality of life and improve public health. We conducted a randomized intervention study to evaluate air pollution impacts of a carbon-finance-approved cookstove in rural South India. We employed real-time monitors to measure indoor concentrations of PM<sub>2.5</sub>, black carbon (BC) and carbon monoxide (CO) in households using carbon-finance-approved stoves and households continuing to use traditional open fire stoves. Implementation of the new cookstoves decreased concentrations of CO and PM<sub>2.5</sub> but increased BC concentrations relative to the traditional stoves.

Although lab studies have clearly demonstrated the potential benefits of cookstove interventions, demonstrating these same benefits in real households is more complex. This work suggests that reduction in indoor pollution from intervention cookstoves might not be occurring in practice to the same extent as is expected from lab evaluation, and that benefits from such interventions should not be assumed.

**Publication**: [Kelp et al., (2018)](https://www.sciencedirect.com/science/article/pii/S2352728517300726){:target="_blank"}

<br />

<font size="+1"><p align="center"><strong>Actionable sampling: Heavy metals air quality monitoring in Portland, OR</strong></p></font>

<figure>
<img src="/assets/img/arsenic_monitoring.png" alt="train fig">
</figure>

<br />

Teaming up with the Oregon Department of Environmental Quality (DEQ), I was an air quality sample assistant during the fall of 2015. I helped install and collect BGI filters and maintained an EPA-validated method sampling site. We created [statewide attention](https://www.portlandmercury.com/BlogtownPDX/archives/2016/02/03/arsenic-cadmium-levels-near-two-se-portland-schools-are-alarmingly-high-state-finds) towards elevated arsenic and cadmium concentrations near two schools (including a kindergarten) in SE Portland. We identified the source of the heavy metal pollution from the Bullseye Glass Co. which then [suspended its use of chromium](https://www.portlandmercury.com/BlogtownPDX/archives/2016/02/04/bullseye-glass-has-suspended-use-of-arsenic-and-cadmium-because-of-air-quality-concerns) in its products. Our monitoring efforts helped lead to the Cleaner Air Oregon regulations written by DEQ and the Oregon Health Authority and are supported by Governor Kate Brown.

**Publication**: [EPA-DEQ certification](https://drive.google.com/file/d/1MBypsl_yBFwdpMGOHG97ZG_KQ9k5zbXS/view)

<br />

<font size="+1"><p align="center"><strong>Measuring coal dust from trains in the Columbia River Gorge, WA</strong></p></font>

<figure>
<img src="/assets/img/gorge_fig.png" alt="train fig">
<figcaption> Images captured from the video camera before and after coal train passage on 8/7/2014 at 17:28 PDT.</figcaption>
</figure>

<br />

Trains powered by diesel fuel travel through the Columbia River Gorge as well as many urban areas in Washington State. Evaluating the air quality impacts from rail traffic for people living near rail lines is hampered by a lack of monitoring data. Emission standards for new and remanufactured locomotives have decreased steadily over the past several decades. Because of the lack of information on PM<sub>2.5</sub> exposure to humans from diesel trains, we sought to measure these air quality effects.

We monitored emissions of diesel PM<sub>2.5</sub> and coal dust from trains in the Columbia River Gorge during summer 2014 and found that the passage of diesel powered open-top coal trains result in nearly twice as much respirable PM<sub>2.5</sub> compared to the passage of diesel-powered freight trains not carrying coal. Furthermore, we witnessed multiple “super-duster” events where the coal dust emissions led to visible dust plumes and the highest PM<sub>2.5</sub> concentrations observed in our study.

**Publication**: [Jaffe et al., (2015)](https://www.sciencedirect.com/science/article/abs/pii/S1309104215000057){:target="_blank"}
