---
permalink: /research/
layout: post
comments: false
image: assets/img/badlands3.jpg
class: research-page

---
<!-- <font size="+3">Research Interests</font>
<font size="+1">
  <p>My work centers on advancing the understanding of atmospheric chemistry and its intersections with human and environmental systems. I am particularly interested in <em>leveraging innovative data science and machine learning techniques to tackle complex challenges in air quality and wildfire smoke management.</em> I enjoy approaching problems from unique perspectives, uncovering insights through the exploration of unconventional methods and data sources.
</p>
</font> -->

<!-- Inserted image (not sideways, full width with auto-scaling) -->
<!-- <div style="text-align: center; margin-top: 20px;">
  <img src="/assets/img/mkelp_group.jpeg" alt="Research group" style="max-width: 100%; height: auto;">
</div>

<br /> -->

<style>
  @media (min-width: 1024px) {
    .research-page {
      max-width: 1300px;
      margin: 0 auto;
      margin-left: -250px; /* Specific for desktop */
      padding: 0 20px;
    }
  }

  @media (max-width: 1023px) {
    .research-page {
      max-width: 100%; /* Full width for mobile */
      margin: 0 auto; /* Center the page */
      margin-left: 0px !important; 
      padding: 0 15px; /* Add padding for smaller screens */
      box-sizing: border-box; /* Ensure padding is included in width */
    }
  }
</style>

<div class="research-page">


<div align="center">
  <h2><strong>Research Questions</strong></h2>
</div> <div style="font-size: 1.2em; line-height: 1.6;">

<p style="margin-bottom: 1.2em;">
    We work to advance our understanding of air quality and its intersections with human and environmental systems. We are particularly interested in leveraging innovative data science and machine learning techniques to tackle complex problems in air pollution modeling and wildfire smoke management. We look to approach problems from unique perspectives, uncovering insights through the exploration of unconventional methods and data sources.
  </p>
<br />
  <!-- Inserted image (not sideways, full width with auto-scaling) -->
  <div style="text-align: center; margin-top: 20px;">
    <img src="/assets/img/mkelp_group.jpeg" alt="Research group" style="max-width: 100%; height: auto;">
  </div>

</div>




  <!-- <font size="+3">Research Interests</font>

  <p>
    My work centers on advancing the understanding of atmospheric chemistry and its intersections with human and environmental systems. I am particularly interested in <em>leveraging innovative data science and machine learning techniques to address complex challenges in air quality and wildfire land/smoke management.</em> I enjoy approaching problems from unique perspectives, uncovering insights through the exploration of unconventional methods and data sources.
  </p> -->

  <br />
  <br />
  <br />
  
  <div align="center">
  <h2><strong>Research Areas</strong></h2>
</div>
  <br />

  <div class="research-section">
    <figure style="padding: 10px; border-radius: 5px; flex: 0 0 50%;">
      <img src="/assets/img/rx_creek.jpeg" alt="Wildfire emissions" style="width: 100%;">
      <figcaption>Estimating the impact of prescribed fire on later wildfire burn severity using Sentinel-2A remote sensing data and land management records.</figcaption>
    </figure>
    <div class="research-content">
      <font size="+2"><p><strong>Wildfire Smoke Modeling and Mitigation</strong></p></font>
      <p>
        Due to a warming climate, a legacy of fire suppression, and expanding development into the wildland-urban interface (WUI), the western US has experienced a recent rise in extreme wildfire seasons. Wildfires not only damage ecosystems and infrastructure but also degrade air quality and pose serious public health risks from smoke exposure. Prescribed ("Rx") fire is often promoted as a policy solution in the western US, yet its use is limited in practice and few studies have evaluated its effectiveness against wildfire impacts. Our research is motivated by key gaps in our understanding: (1) we lack observational and modeling systems to accurately project how scaling Rx fire useage would affect air quality and health outcomes in the western US; and (2) the efficacy of past Rx fire treatments remains poorly quantified across varied landscapes and fire seasons. It is unclear whether expanding Rx burning will reduce wildfire risk or simply add to the smoke burden without preventing future fires. Some of our recent work shows that Rx fire treatments, while modestly effective, are frequently least successful in the WUI, a central focus of wildfire policy. Such findings highlight the limitations of current wildfire strategies and underscore the need for data-driven, policy-relevant approaches to guide the proposed expansion of Rx fire.
      </p>
      <p>
        <br />
        <strong>Publications:</strong> 
        <a href="https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2025AV001682" target="_blank">Kelp et al. (2025) <em>AGU Adv.</em></a>, <a href="https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2022EF003468" target="_blank">Kelp et al. (2023) <em>Earth's Future</em></a>
        <!-- <a href="https://eartharxiv.org/repository/view/8286/" target="_blank">Kelp et al., (preprint)</a>, -->

      </p>
            <p>
        <strong>Mentored Publications:</strong>
        <a href="https://pubs.acs.org/doi/10.1021/acs.est.5c01914" target="_blank">Chung et al. (2025) <em>ES&T</em></a>,       </p>
      <p>
        <strong>Co-Authored Wildfire Publications:</strong>
        <a href="https://www.pnas.org/doi/10.1073/pnas.2421903122" target="_blank">Feng et al. (2025) <em>PNAS</em></a>, <a href="https://www.nature.com/articles/s41586-025-09611-w" target="_blank">Qiu et al. (2025) <em>Nature</em></a>, 
        <a href="https://pubs.acs.org/doi/10.1021/acs.est.4c05922" target="_blank">Qiu et al. (2024) <em>ES&T</em></a>, 
        <a href="https://www.publish.csiro.au/WF/WF23148" target="_blank">Liu et al. (2024) <em>Int J Wildland Fire</em></a>
      </p>

      <p>
        <strong>Points for Policymakers:</strong>
        <a href="https://makotokelp.com/assets/woods-prescribed-fire-rb.pdf" target="_blank">Prescribed fire research brief</a>
      </p>


    </div>
  </div>

<br />

  <div class="research-section">
    <figure style="padding: 10px; border-radius: 5px; flex: 0 0 50%;">
      <img src="/assets/img/SAE.jpeg" alt="Machine-learned solver" style="width: 100%;">
      <figcaption>Mechanistic interpretability of emerging atmospheric AI foundation models.</figcaption>
    </figure>
    <div class="research-content">
      <font size="+2"><p><strong>Deep Learning Atmospheric Chemistry</strong></p></font>
      <p>   
        Ozone is an air pollutant that harms human health, damages vegetation, and acts as a short-lived climate forcer. Despite being the most-measured trace gas in our observational history, global atmospheric models still disagree on even basic ozone trends and spatial patterns. Accurately predicting ozone requires capturing nearly every major process in the atmosphere (e.g., emissions, chemistry, stratosphere-troposphere exchange, and boundary layer mixing). Few problems in geoscience are as well-observed and yet as difficult to predict, which makes ozone a particularly revealing test for AI. Our past work explored how AI can emulate and replace computationally costly components of global atmospheric models for fast, stable simulations. Our current research probes what AI foundation models actually learn about atmospheric chemistry and the extent to which they can complement 
        (or substitute) for conventional process-based models. We work towards physically consistent foundation models that blend data-driven and mechanistic components to better diagnose what drives ozone bias.

        <!-- Global models of atmospheric chemistry are computationally expensive. The chemical solver that integrates the large-dimensional coupled systems of kinetic equations describing the chemical mechanism is a bottleneck. Machine learning (ML) could be transformative for reducing the cost of an atmospheric chemistry simulation by replacing the chemical solver with a faster emulator. Our past work found that ML chemical solvers experience rapid error growth and become unstable over time. This challenge was addressed by introducing physical constraints into the ML architecture and training the ML solver online synchronously within the global atmospheric chemistry model. This approach enabled, for the first time, full-year global simulations of air quality using an embedded neural network solver. However, challenges remain in extending ML solvers to more complex chemical mechanisms and in reducing errors associated with long-term chemical aging. Our ongoing research focuses on addressing these limitations by developing transformer-based architectures for improved spatial/temporal generalization, applying transfer learning from atmospheric AI foundation models, and leveraging self-supervised training algorithms specialized for remote sensing data. These efforts ultimately aim to develop accurate, stable, and physically consistent ML models to enable the simulation of comprehensive atmospheric chemistry in climate and Earth System models. -->

      </p>
      <p>
        <br />
        <strong>Publications:</strong> 
        <a href="https://doi.org/10.1029/2021MS002926" target="_blank">Kelp et al. (2022) <em>JAMES</em></a>, 
        <a href="https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1029/2020JD032759" target="_blank">Kelp et al. (2020) <em>JGR: Atmos</em></a>,
        <a href="https://arxiv.org/abs/1808.03874" target="_blank">Kelp et al. (2018) <em>ArXiv</em></a>

      </p>
      <p>
        <strong>Future Priorities of AI in Air Quality: </strong>
        <a href="https://gmd.copernicus.org/articles/18/8777/2025/" target="_blank">Highlight Paper on AI for Tropospheric Ozone Research (2025)</a>, <a href="https://openreview.net/forum?id=JuEZ5F8E3Z" target="_blank">NeurIPS AI4Science Dataset Competition Winning Paper (2025)</a>
      </p>
    </div>
  </div>

<br />

  <div class="research-section">
    <figure style="padding: 10px; border-radius: 5px; flex: 0 0 50%;">
      <img src="/assets/img/sensors2.jpg" alt="PM2.5 sensor locations" style="width: 100%;">
      <figcaption>Distribution of sensor locations in the EPA monitoring network compared to those identified as optimal by compressed sensing (mrDMD) in the western US. </figcaption>
    </figure>
    <div class="research-content">
      <font size="+2"><p><strong>Data-Driven Air Pollution Sensing</strong></p></font>
      <p>
        Despite major investments in air quality (AQ) monitoring, existing sensor networks often fail to capture extreme air pollution. We use data-driven methods to improve the design of sensor networks, air quality forecasts, and environmental early warning systems. In one national scale study, we applied compressed sensing algorithms, a signal processing method that uncovers important spatiotemporal patterns found in data, to determine optimal AQ sensor locations based on recent pollution trends. This analysis revealed major gaps in the current EPA's monitoring network across the western US, particularly in regions affected by wildfire smoke. In a related study, we incorporated equity constraints into the sensor network optimization to improve coverage in historically segregated neighborhoods in cities such as St. Louis and Houston. These approaches provide a foundation for rethinking how we design AQ monitoring networks to better capture extreme events and ensure more equitable coverage. At the same time, commercial platforms increasingly deliver AQ forecasts through proprietary systems, raising concerns about transparency and public accessibility. These systems are likely to become more prevalent in the coming decade due to the rapid commercialization of environmental data and advances in AI and cloud computing. In response, our research is guided by a set of core questions: What are the early warning signals of extreme air pollution (fires, inversions, smog)? Can open data outperform commercial forecasts? 
      </p>
      <p>
        <br />
        <strong>Publications:</strong> 
        <a href="https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2023GH000834" target="_blank">Kelp et al. (2023) <em>GeoHealth</em></a>, <a href="https://iopscience.iop.org/article/10.1088/1748-9326/acf0b7" target="_blank">Kelp et al. (2023) <em>ERL</em></a>, 
        <a href="https://iopscience.iop.org/article/10.1088/1748-9326/ac548f" target="_blank">Kelp et al. (2022) <em>ERL</em></a>
      </p>
      <p>
        <strong>Co-Authored Sensor Publications:</strong>
        <a href="https://www.science.org/doi/full/10.1126/sciadv.adq1071" target="_blank">Kawano et al. (2025) <em>Sci. Adv.</em></a>, 
        <a href="https://pubs.acs.org/doi/10.1021/acs.est.1c07005" target="_blank">Yang et al. (2022) <em>ES&T</em></a>
      </p>
    </div>
  </div>

<!-- </div> -->


<!-- <div class="research-page">

  <font size="+3">Past Projects</font>

  <br />

  <div class="research-section">
    <figure style="border: 2px solid #fff; padding: 10px; border-radius: 5px; flex: 0 0 50%;">
      <img src="/assets/img/cda_o3.png" alt="Chemical data assimilation figure" style="width: 100%;">
      <figcaption>Interpolated contour plots of ozone concentrations as a function of latitude and altitude in April-May 2018. Observations from the ATom-4 aircraft campaign are compared with the Control and Full Assimilation simulations in GEOS-CF sampled along the aircraft flight tracks.</figcaption>
    </figure>
    <div class="research-content">
      <font size="+2"><p>Chemical Data Assimilation for Atmospheric Composition</p></font>
      <p>
        The NASA Goddard Earth Observing System Composition Forecast system (GEOS-CF) provides global near-real-time analyses and forecasts of atmospheric composition. The current version of GEOS-CF builds on the GEOS general circulation model with Forward Processing assimilation of meteorological data (GEOS-FP) and includes detailed GEOS-Chem tropospheric and stratospheric chemistry. Here we add 3D variational data assimilation in GEOS-CF to assimilate satellite observations of ozone including MLS vertical profiles, OMI total columns, and AIRS and IASI hyperspectral 9.6 μm radiances. We find that the detailed tropospheric chemistry in GEOS-CF significantly improves the simulated background ozone fields relative to previous versions of the GEOS model, allowing for specification of smaller background errors in assimilation and resulting in smaller assimilation increments to correct the simulated ozone. Comparisons to independent ozonesonde and aircraft (ATom-4) observations for 2018 show significant GEOS-CF improvement from the assimilation, particularly in the extratropical upper troposphere.

      </p>
      <p>
        <br />
        <strong>Publications:</strong> 
        <a href="https://iopscience.iop.org/article/10.1088/1748-9326/acf0b7" target="_blank">Kelp et al., (2023) <em>ERL</em></a>
      </p>
    </div>
  </div>

<br />

  <div class="research-section">
    <figure style="border: 2px solid #fff; padding: 10px; border-radius: 5px; flex: 0 0 50%;">
      <img src="/assets/img/LA_roads_fig.png" alt="Vehicle emissions figure" style="width: 90%;">
      <figcaption>Road and street classifications in Los Angeles County with county base map provided by the U.S. Census Bureau's Master Address File / Topologically Integrated Geographic Encoding and Referencing (MAF/TIGER) Database (MTDB). (src credit: Yurika Harada)</figcaption>
    </figure>
    <div class="research-content">
      <font size="+2"><p>Vehicle Emission Factors for Area-Wide Mobile Monitoring</p></font>
      <p>
        On-road vehicle emissions are a significant source of outdoor air pollution, which pose a severe human health risk, especially for those who live near busy roads. A city's vehicle fleet can determine the levels of risk and exposure for residences as emissions differ for gasoline- vs. diesel-powered vehicles. Most research sampling mobile source emissions in urban traffic involves “vehicle chase” studies of exhaust plumes from individual vehicles which may not be representative of the average emissions for a given area.
        <br />
        <br />
        We create a statistical model from measurements obtained from continuously moving platforms to estimate area-wide average vehicle emission factors of neighborhoods. These model predictions are used to estimate emission factors by source-related features within a city. Furthermore, our model can calculate separately light-duty and heavy-duty vehicle emission factors for a study area while also separating out high-emitter vehicles that may artificially skew emission factor estimates. Study areas include Los Angeles, USA and Chengdu, China.

      </p>
      <p>
        <br />
        <strong>Publications:</strong> 
        <a href="https://www.sciencedirect.com/science/article/pii/S1352231019308519" target="_blank">Kelp et al., (2020) <em>Atmos. Env.</em></a>
      </p>
      <p>
        <strong>Related Publications:</strong> 
        <a href="https://www.sciencedirect.com/science/article/pii/S0048969719317140" target="_blank">Wen et al., (2019)</a>
      </p>
    </div>
  </div>

<!-- <br />

  <div class="research-section">
    <figure style="border: 2px solid #fff; padding: 10px; border-radius: 5px; flex: 0 0 50%;">
      <img src="/assets/img/cookstove_fig.jpg" alt="Cookstove intervention figure" style="width: 70%;">
      <figcaption>Diurnal distribution of real-time PM<sub>2.5</sub> concentrations with 10-min resolution. “S1” (A) is the pre-intervention baseline and “S2” (B) is the post-intervention follow-up using cookstoves.</figcaption>
    </figure>
    <div class="research-content">
      <font size="+2"><p>Indoor Air Pollution from Cookstove Interventions in S. India</p></font>
      <p>
        Biomass combustion from residential cookstoves is a major source of indoor air pollution and a large contributor to the global burden of disease. Investment of resources into rural energy intervention programs has great potential to improve household air quality in developing countries and thus increase quality of life and improve public health. We conducted a randomized intervention study to evaluate air pollution impacts of a carbon-finance-approved cookstove in rural South India. We employed real-time monitors to measure indoor concentrations of PM<sub>2.5</sub>, black carbon (BC) and carbon monoxide (CO) in households using carbon-finance-approved stoves and households continuing to use traditional open fire stoves. Implementation of the new cookstoves decreased concentrations of CO and PM<sub>2.5</sub>, but increased BC concentrations relative to the traditional stoves.
        <br />
        <br />
        Although lab studies have clearly demonstrated the potential benefits of cookstove interventions, achieving these same benefits in real households is more complex. This work suggests that reduction in indoor pollution from intervention cookstoves might not be occurring in practice to the same extent as is expected from lab evaluation, and that benefits from such interventions should not be assumed.
      </p>
      <p>
        <br />
        <strong>Publications:</strong> 
        <a href="https://www.sciencedirect.com/science/article/pii/S2352728517300726" target="_blank">Kelp et al., (2018)</a>
      </p>
    </div>
  </div>

<!-- <br />

  <div class="research-section">
    <figure style="border: 2px solid #fff; padding: 10px; border-radius: 5px; flex: 0 0 50%;">
        <img src="/assets/img/arsenic_monitoring.png" alt="Heavy metals monitoring figure" style="width: 100%;">
        <figcaption> </figcaption>
    </figure>
    <div class="research-content">
        <font size="+2"><p>Heavy Metals Air Quality Monitoring in Portland, OR</p></font>
        <p>
            Teaming up with the Oregon Department of Environmental Quality (DEQ), I was an air quality sample assistant during the fall of 2015. I helped install and collect BGI filters and maintained an EPA-validated method sampling site. We created 
            <a href="https://www.portlandmercury.com/BlogtownPDX/archives/2016/02/03/arsenic-cadmium-levels-near-two-se-portland-schools-are-alarmingly-high-state-finds" target="_blank">statewide attention</a> 
            to elevated arsenic and cadmium concentrations near two schools (including a kindergarten) in SE Portland. We identified the source of the heavy metal pollution as coming from the Bullseye Glass Co. which then 
            <a href="https://www.portlandmercury.com/BlogtownPDX/archives/2016/02/04/bullseye-glass-has-suspended-use-of-arsenic-and-cadmium-because-of-air-quality-concerns" target="_blank">suspended its use of chromium</a> 
            in its products. Our monitoring efforts helped lead to the Cleaner Air Oregon regulations written by DEQ and the Oregon Health Authority, and are supported by Governor Kate Brown.
        </p>
    
    <p>
        <br />
        <strong>Publications:</strong> 
        <a href="https://drive.google.com/file/d/1MBypsl_yBFwdpMGOHG97ZG_KQ9k5zbXS/view" target="_blank">EPA-DEQ certification</a>
      </p>
    </div>
</div> -->

<!-- <br />

  <div class="research-section">
    <figure style="border: 2px solid #fff; padding: 10px; border-radius: 5px; flex: 0 0 50%;">
      <img src="/assets/img/gorge_fig.png" alt="Coal dust monitoring figure" style="width: 100%;">
      <figcaption>Images captured from the video camera before and after coal train passage on 8/7/2014 at 17:28 PDT.</figcaption>
    </figure>
    <div class="research-content">
      <font size="+2"><p>Measuring Coal Dust from Trains in the Columbia River Gorge</p></font>
      <p>
        Trains powered by diesel fuel travel through the Columbia River Gorge as well as many urban areas in Washington State. Evaluating the air quality impacts from rail traffic on people living near rail lines is hampered by a lack of monitoring data. Emission standards for new and remanufactured locomotives have decreased steadily over the past several decades. Because of the lack of information on PM<sub>2.5</sub> exposure to humans from diesel trains, we sought to measure these air quality effects.
        <br />
        <br />
        During summer 2014, we monitored emissions of diesel PM<sub>2.5</sub> and coal dust from trains in the Columbia River Gorge and found that the transit of diesel powered open-top coal trains result in nearly twice as much respirable PM<sub>2.5</sub> compared to the passage of diesel-powered freight trains not carrying coal. Furthermore, we witnessed multiple “super-duster” events during which the coal dust emissions led to visible dust plumes and the highest PM<sub>2.5</sub> concentrations observed in our study.

      </p>
      <p>
        <br />
        <strong>Publications:</strong> 
        <a href="https://www.sciencedirect.com/science/article/abs/pii/S1309104215000057" target="_blank">Jaffe et al., (2015)</a>
      </p>
    </div>
  </div>

</div> -->  


<!-- 
 <h2><strong>Research Questions</strong></h2>
 <div style="font-size: 1.2em; line-height: 1.6;">

<p style="margin-bottom: 1.2em;">
    My work centers on advancing the understanding of atmospheric chemistry and its intersections with human and environmental systems. I am particularly interested in 
    <em>leveraging innovative data science and machine learning techniques to tackle complex challenges in air quality modeling and wildfire smoke management.</em> 
    I enjoy approaching problems from unique perspectives, uncovering insights through the exploration of unconventional methods and data sources.
  </p>
<br />
  Inserted image (not sideways, full width with auto-scaling)
  <div style="text-align: center; margin-top: 20px;">
    <img src="/assets/img/mkelp_group.jpeg" alt="Research group" style="max-width: 100%; height: auto;">
  </div>

</div> -->

