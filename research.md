---
layout: page
title: "Research"
permalink: /research/
---

<p class="page-intro">
  We use physical modeling, IoT sensing technologies, lifecycle assessment, and various deep learning tools to decipher sustainability challenges in cities. 
</p>

<strong>Full publication list can be found at at my Google Scholar and ORCID pages </strong>.

<div class="quicklinks">
  <a class="quick-card" href="https://scholar.google.com/citations?user=v_tp904AAAAJ&hl=en" target="_blank" rel="noopener">
    <div class="quick-card-title">Google Scholar</div>
  </a>
  <a class="quick-card" href="https://orcid.org/0000-0002-1874-2702">
    <div class="quick-card-title">ORCID</div>
  </a>
</div>

<section id="sensing" class="research-section">
  <h2>Urban Environmental Sensing</h2>
<div class="scroll-container">
    <div class="card clickable-card" onclick="openModal('modal-s1')" style="background-image: url('{{ site.baseurl }}/assets/research/plumetest.jfif');">
      <h3>Plume Chasing</h3>
    </div>
    <div class="card clickable-card" onclick="openModal('modal-s2')" style="background-image: url('{{ site.baseurl }}/assets/research/crowdsensing.png');">
      <h3>Crowdsourced Sensing</h3>
    </div>
    <div class="card clickable-card" onclick="openModal('modal-s3')" style="background-image: url('{{ site.baseurl }}/assets/research/threemonkeys.jpg');">
      <h3>Multimodal Exposures</h3>
    </div>
  </div>
</section>

<section id="energy" class="research-section">
  <h2>Transport Energy Transition</h2>
  <div class="scroll-container">
    <div class="card clickable-card" onclick="openModal('modal-e1')" style="background-image: url('{{ site.baseurl }}/assets/research/onroademissions.jpg');">
      <h3>On-Road Emission Inventory</h3>
    </div>
    <div class="card clickable-card" onclick="openModal('modal-e2')" style="background-image: url('{{ site.baseurl }}/assets/research/hard2abate.png');">
      <h3>Hard-to-Abate Modes</h3>
    </div>
    <div class="card clickable-card" onclick="openModal('modal-e3')" style="background-image: url('{{ site.baseurl }}/assets/research/physicalmodel.png');">
      <h3>Physical Emissions Modeling</h3>
    </div>
  </div>
</section>

<section id="modeling" class="research-section">
  <h2>Data-Driven Modeling</h2>
  <div class="scroll-container">
    <div class="card clickable-card" onclick="openModal('modal-m1')" style="background-image: url('{{ site.baseurl }}/assets/research/wildfire.jpg');">
      <h3>Wildfire Smoke Attribution</h3>
    </div>
    <div class="card clickable-card" onclick="openModal('modal-m2')" style="background-image: url('{{ site.baseurl }}/assets/research/IOcontinuum.png');">
      <h3>Outdoor-Indoor Continuum</h3>
    </div>
    <div class="card clickable-card" onclick="openModal('modal-m3')" style="background-image: url('{{ site.baseurl }}/assets/research/exposuregap.jpg');">
      <h3>Hyperlocal Exposure Modeling</h3>
    </div>
  </div>
</section>

<div id="modal-s1" class="modal-overlay" onclick="closeModal('modal-s1')">
  <div class="modal-container" onclick="event.stopPropagation()">
    <div class="modal-header">
      <h2>Emission Compliance Failed for Larger Vehicles</h2>
      <span class="close-btn" onclick="closeModal('modal-s1')">&times;</span>
    </div>
    <div id="modalBody-s1" class="modal-body" style="max-height: 70vh;" onscroll="checkModalScroll('modalBody-s1', 'btn-s1')">            
      <div class="modal-text">
        <p><i>*Contributed by Dr. Zeyu ZHANG*</i></p>
        <p>Urban air quality suffers disproportionately from a fraction of heavy-duty diesel vehicles (HDDVs). Existing regulations rely on lab tests that fail to capture real-world, high-emitting behaviors. We deployed a mobile plume-chasing platform equipped with fast-response gas analyzers across Hong Kong to test HDDVs in their natural environment.</p>  
        <figure style="margin: 2.5rem 0; text-align: left;">
          <img src="{{ site.baseurl }}/assets/research/plumechasing1.jpg" alt="Figure 1" style="width: 66%; height: auto; border-radius: 12px; box-shadow: 0 4px 15px rgba(18,59,93,0.1);">
          <figcaption style="font-size: 0.9rem; color: #607487; margin-top: 0.8rem; font-style: italic;">
            Figure 1: Plume chasing instrumentation setup
          </figcaption>
        </figure>
        <p>By translating fuel-based measurements into distance- and power-based emission factors, we found that NOX emissions are highly sensitive to road grade and routinely exceed regulatory baselines by over twofold. Shockingly, around <strong>10% of light goods vehicles and 22% of heavy goods vehicles</strong> emit NOX at more than double the Euro IV limits. Removing these "super-emitters", who represent just <strong>14% of the fleet</strong>, could slash goods-vehicle NOX emissions by <strong>31%</strong>.</p>        
        <figure style="margin: 2.5rem 0; text-align: left;">
          <img src="{{ site.baseurl }}/assets/research/plumechasing2.jpg" alt="Figure 2" style="width: 66%; height: auto; border-radius: 12px; box-shadow: 0 4px 15px rgba(18,59,93,0.1);">
          <figcaption style="font-size: 0.9rem; color: #607487; margin-top: 0.8rem; font-style: italic;">
            Figure 2: Observed emission standard compliance in heavy-duty (above) and light-duty (below) trucks 
          </figcaption>
        </figure>        
        <p>This work highlights mobile plume-chasing as a highly cost-effective, scalable tool for screening high-emitting vehicles and enforcing environmental compliance in dense, mountainous cities.</p>        
        <p><em></em></p>
      </div>
    </div>  
    <button id="btn-s1" class="modal-back-to-top" onclick="scrollModalToTop('modalBody-s1')">↑ Top</button>    
  </div>
</div>

<div id="modal-s2" class="modal-overlay" onclick="closeModal('modal-s2')">
  <div class="modal-container" onclick="event.stopPropagation()">
    <div class="modal-header">
      <h2>Democratizing Air Sensing Through Remote Calibration</h2>
      <span class="close-btn" onclick="closeModal('modal-s2')">&times;</span>
    </div>
    <div id="modalBody-s2" class="modal-body" style="max-height: 70vh;" onscroll="checkModalScroll('modalBody-s2', 'btn-s2')">
      <div class="modal-text">
        <p><i>*Contributed by Wenyu WANG*</i></p>
        <p>The democratization of air quality monitoring through low-cost sensor (LCS) networks promises unprecedented, block-by-block visibility into urban pollution. Yet, poor data reliability has largely relegated these networks to citizen science rather than rigorous policymaking. Traditional calibration requires physically co-locating sensors with "gold standard" reference stations—an unscalable bottleneck.</p>
        <figure style="margin: 2.5rem 0; text-align: left;">
          <img src="{{ site.baseurl }}/assets/research/remocalib1.png" alt="Figure 1" style="width: 66%; height: auto; border-radius: 12px; box-shadow: 0 4px 15px rgba(18,59,93,0.1);">
          <figcaption style="font-size: 0.9rem; color: #607487; margin-top: 0.8rem; font-style: italic;">
            Figure 1: The remote calibration concept
          </figcaption>
        </figure>  
        <p>We developed a novel <strong>"remote calibration"</strong> framework that eliminates the need for physical collocation. By matching <strong>over 33 million hourly observations</strong> from the largest US LCS network against reference stations during periods of low regional PM2.5 variability, we generated metropolis-specific calibration models. This approach successfully corrected systematic sensor biases across the ten largest US metropolitan areas.</p>
        <figure style="margin: 2.5rem 0; text-align: left;">
          <img src="{{ site.baseurl }}/assets/research/remocalib2.png" alt="Figure 2" style="width: 66%; height: auto; border-radius: 12px; box-shadow: 0 4px 15px rgba(18,59,93,0.1);">
          <figcaption style="font-size: 0.9rem; color: #607487; margin-top: 0.8rem; font-style: italic;">
            Figure 2: Hyperlocal air sensing in NYC during June 2023 Canadian Wildfire Event (above: only EPA stations; below: with calibrated LCS network)
          </figcaption>
        </figure>  
        <p>Our calibrated data revealed a stark reality: while LCS networks dramatically reduce spatial monitoring disparities, severe inequities persist, with African American communities remaining the least covered. By proving that crowd-sourced data can be systematically elevated to scientific-grade accuracy, this methodology expedites a paradigm shift toward equitable, hyperlocal air surveillance.</p>        
      </div>
    </div>
    <button id="btn-s2" class="modal-back-to-top" onclick="scrollModalToTop('modalBody-s2')">↑ Top</button>
  </div>
</div>

<div id="modal-s3" class="modal-overlay" onclick="closeModal('modal-s3')">
  <div class="modal-container" onclick="event.stopPropagation()">
    <div class="modal-header">
      <h2>See No Evil?</h2>
      <span class="close-btn" onclick="closeModal('modal-s3')">&times;</span>
    </div>
    <div id="modalBody-s3" class="modal-body" style="max-height: 70vh;" onscroll="checkModalScroll('modalBody-s3', 'btn-s3')">
      <div class="modal-text">
        <p><i>*Contributed by Xiaotong ZHANG*</i></p>
        <p>Cities are experienced through a symphony of senses, yet urban planning often prioritizes the visual landscape while treating sound, micro-climate, and air quality as afterthoughts. To quantify this multi-sensory urban experience, we combined drive-by environmental sensing—capturing street view imagery, noise levels, temperature, humidity, and PM2.5—with geotagged social media data serving as a proxy for human sentiment in the Bronx, New York.</p>
        <figure style="margin: 2.5rem 0; text-align: left;">
          <img src="{{ site.baseurl }}/assets/research/sentiment1.jpg" alt="Figure 1" style="width: 66%; height: auto; border-radius: 12px; box-shadow: 0 4px 15px rgba(18,59,93,0.1);">
          <figcaption style="font-size: 0.9rem; color: #607487; margin-top: 0.8rem; font-style: italic;">
            Figure 1: Conceptual research framework - the multi-sensory approach
          </figcaption>
        </figure>    
        <p>Using machine learning and natural language processing, we mapped how the physical environment interacts with emotional valence. Our results confirm that while visual aesthetics powerfully drive positive sentiment, the invisible environment plays a massive, underappreciated role. <strong>High noise levels are strongly linked to negative sentiment and annoyance</strong>, outpacing even poor visual environments. Meanwhile, <strong>ambient temperature significantly depresses positivity</strong>, highlighting the emotional toll of the urban heat island effect.</p>
        <figure style="margin: 2.5rem 0; text-align: left;">
          <img src="{{ site.baseurl }}/assets/research/sentiment2.svg" alt="Figure 2" style="width: 66%; height: auto; border-radius: 12px; box-shadow: 0 4px 15px rgba(18,59,93,0.1);">
          <figcaption style="font-size: 0.9rem; color: #607487; margin-top: 0.8rem; font-style: italic;">
            Figure 2: The factors that drive expressed positive (left) and negative (right) sentiments
          </figcaption>
        </figure>    
        <p>This underscores a crucial directive for sustainable urban design: creating livable, happy cities requires holistic, multi-sensory interventions—such as deploying green infrastructure that not only beautifies streets, but simultaneously buffers traffic noise and provides thermal relief.</p>        
      </div>
    </div>
    <button id="btn-s3" class="modal-back-to-top" onclick="scrollModalToTop('modalBody-s3')">↑ Top</button>
  </div>
</div>

<div id="modal-e1" class="modal-overlay" onclick="closeModal('modal-e1')">
  <div class="modal-container" onclick="event.stopPropagation()">
    <div class="modal-header">
      <h2>HK Vehicles More Polluted than Expected</h2>
      <span class="close-btn" onclick="closeModal('modal-e1')">&times;</span>
    </div>
    <div id="modalBody-e1" class="modal-body" style="max-height: 70vh;" onscroll="checkModalScroll('modalBody-e1', 'btn-e1')">
      <div class="modal-text">
        <p><i>*Contributed by Dr. Zeyu ZHANG*</i></p>
        <p>In our recent study, we demonstrated that neglecting topography fundamentally skews our understanding of urban emissions. By fusing multi-sourced traffic & GIS data and validating the results via real-world plume-chasing measurements, we constructed a dynamic, grade-inclusive emission inventory.</p>
        <figure style="margin: 2.5rem 0; text-align: left;">
          <img src="{{ site.baseurl }}/assets/research/hkemissions1.jpg" alt="Figure 1" style="width: 66%; height: auto; border-radius: 12px; box-shadow: 0 4px 15px rgba(18,59,93,0.1);">
          <figcaption style="font-size: 0.9rem; color: #607487; margin-top: 0.8rem; font-style: italic;">
            Figure 1: Emission differences w/wo road grade consideration
          </figcaption>
        </figure>
        <p>The results reveal a stark reality: downhill emission reductions fail to cancel out the massive fuel penalties of uphill climbs. Factoring in road grade increases Hong Kong’s citywide vehicular carbon and air pollutant estimates by <strong>10% to 30%</strong>. More critically, topography dramatically alters the spatial distribution of pollution. Over half of the city's road segments deviate by more than 10% from traditional flat-road estimates. This clusters emission hotspots in topographically complex neighborhoods with heavy-duty traffic, directly impacting local exposure.</p>
        <figure style="margin: 2.5rem 0; text-align: left;">
          <img src="{{ site.baseurl }}/assets/research/hkemissions2.jpg" alt="Figure 2" style="width: 66%; height: auto; border-radius: 12px; box-shadow: 0 4px 15px rgba(18,59,93,0.1);">
          <figcaption style="font-size: 0.9rem; color: #607487; margin-top: 0.8rem; font-style: italic;">
            Figure 2: Decarbonization projection of the EV sector (w/wo road grade)
          </figcaption>
        </figure>        
        <p>Furthermore, this high-resolution modeling exposes vulnerabilities in current climate policy. When projecting these grade-adjusted emissions, we found that Hong Kong’s ambitious 2035 transportation decarbonization target could face an approximate <strong>seven-year delay</strong> without a substantially cleaner power grid and accelerated electric vehicle adoption. For densely populated, hilly cities, these findings offer a clear directive: effective low-carbon transitions and pollution control demand that we model our urban systems in all three dimensions.</p>
        <p><em>*Full paper is available at https://doi.org/10.1016/j.trd.2026.105270.*</em></p>
      </div>
    </div>
    <button id="btn-e1" class="modal-back-to-top" onclick="scrollModalToTop('modalBody-e1')">↑ Top</button>
  </div>
</div>

<div id="modal-e2" class="modal-overlay" onclick="closeModal('modal-e2')">
  <div class="modal-container" onclick="event.stopPropagation()">
    <div class="modal-header">
      <h2>Energy Transition: A Global Need, A Local Deed</h2>
      <span class="close-btn" onclick="closeModal('modal-e2')">&times;</span>
    </div>
    <div id="modalBody-e2" class="modal-body" style="max-height: 70vh;" onscroll="checkModalScroll('modalBody-e2', 'btn-e2')">
      <div class="modal-text">
        <p><i>*On-going work by Peimin WU*</i></p>
        <p>We are investigating the best energy transition pathyways for hard-to-abate transport modes in the HK context. The biggest challenge lies in the blackbox nature of the local power grids operation.</p>
      </div>
    </div>
    <button id="btn-e2" class="modal-back-to-top" onclick="scrollModalToTop('modalBody-e2')">↑ Top</button>
  </div>
</div>

<div id="modal-e3" class="modal-overlay" onclick="closeModal('modal-e3')">
  <div class="modal-container" onclick="event.stopPropagation()">
    <div class="modal-header">
      <h2>In Progress to Eliminate Tailpipe Emissions</h2>
      <span class="close-btn" onclick="closeModal('modal-e3')">&times;</span>
    </div>
    <div id="modalBody-e3" class="modal-body" style="max-height: 70vh;" onscroll="checkModalScroll('modalBody-e3', 'btn-e3')">
      <div class="modal-text">
        <p>For decades, researchers and regulators have relied on rigid regulatory emission models that struggle to reflect the complex realities of modern traffic. Built upon manually tuned parameters and predefined speed bins, these traditional tools often misclassify emissions and fail to accurately capture the dynamic behaviors of transitional technologies, such as Hybrid Electric Vehicles (HEVs), under real-world, aggressive driving conditions.</p>  
        <figure style="margin: 2.5rem 0; text-align: left;">
          <img src="{{ site.baseurl }}/assets/research/emissionmodel1.jpg" alt="Figure 1" style="width: 66%; height: auto; border-radius: 12px; box-shadow: 0 4px 15px rgba(18,59,93,0.1);">
          <figcaption style="font-size: 0.9rem; color: #607487; margin-top: 0.8rem; font-style: italic;">
            Figure 1: Conceptual illustration of the Greedy modal-binning algorithm
          </figcaption>
        </figure>         
        <p>To bridge this gap, we developed novel, data-driven modal emission frameworks powered by extensive on-road Portable Emission Measurement System (PEMS) data. First, we engineered an optimized Greedy algorithm that <strong>autonomously defines vehicle operating boundaries</strong>. By eliminating subjective, manual binning and integrating internal engine parameters, this methodology improved predictive accuracy for highly variable pollutants like NOx and CO by roughly <strong>30%</strong>. We then expanded this high-resolution modeling to decipher the complex, dual-powertrain dynamics of HEVs, utilizing machine learning to predict electric motor engagement in real time before estimating tailpipe output.</p>
        <figure style="margin: 2.5rem 0; text-align: left;">
          <img src="{{ site.baseurl }}/assets/research/emissionmodel2.jpg" alt="Figure 2" style="width: 66%; height: auto; border-radius: 12px; box-shadow: 0 4px 15px rgba(18,59,93,0.1);">
          <figcaption style="font-size: 0.9rem; color: #607487; margin-top: 0.8rem; font-style: italic;">
            Figure 2: Percentage emission reduction after adopting HEV in Toronto and Beijing, where negative emission reductions refer to an increase in emissions.
          </figcaption>
        </figure>         
        <p>Applying these advanced models across diverse metropolitan traffic profiles—comparing the congested flows of Beijing with the aggressive driving patterns of Toronto—revealed a critical insight. While HEVs are capable of slashing carbon and pollutant emissions by over 50%, aggressive driving severely erodes these benefits. Ultimately, upgrading our physical modeling from static lab approximations to dynamic, real-world algorithms is essential for policymakers to accurately forecast decarbonization trajectories and design targeted traffic management strategies that maximize the potential of low-carbon fleets.</p>
      </div>
    </div>
    <button id="btn-e3" class="modal-back-to-top" onclick="scrollModalToTop('modalBody-e3')">↑ Top</button>
  </div>
</div>

<div id="modal-m1" class="modal-overlay" onclick="closeModal('modal-m1')">
  <div class="modal-container" onclick="event.stopPropagation()">
    <div class="modal-header">
      <h2>The Not-So-Solid Basis of Wildfire Impact Research</h2>
      <span class="close-btn" onclick="closeModal('modal-m1')">&times;</span>
    </div>
    <div id="modalBody-m1" class="modal-body" style="max-height: 70vh;" onscroll="checkModalScroll('modalBody-m1', 'btn-m1')">
      <div class="modal-text">
        <p><i>*On-going work by Wenyu WANG*</i></p>
        <p>Wildfire is one of the most critically deteriorated climate change outcomes across the globe. It is threatening the lives of billions. But what if the previous basis of assessing wildfire smoke's environmental impacts is poorly structured? We are using large-scale air quality data to quantify the actual contribution of wildfires to local air pollution.</p>
        </div>
    </div>
    <button id="btn-m1" class="modal-back-to-top" onclick="scrollModalToTop('modalBody-m1')">↑ Top</button>
  </div>
</div>

<div id="modal-m2" class="modal-overlay" onclick="closeModal('modal-m2')">
  <div class="modal-container" onclick="event.stopPropagation()">
    <div class="modal-header">
      <h2>The Uninvited Guest</h2>
      <span class="close-btn" onclick="closeModal('modal-m2')">&times;</span>
    </div>
    <div id="modalBody-m2" class="modal-body" style="max-height: 70vh;" onscroll="checkModalScroll('modalBody-m2', 'btn-m2')">
      <div class="modal-text">
        <p><i>*On-going work by Dr. Hui DAI*</i></p>
        <p>People spend most of their time indoors. What are the key factors determining our air pollution exposure when we work, leisure, eat, and rest?</p>
      </div>
    </div>
    <button id="btn-m2" class="modal-back-to-top" onclick="scrollModalToTop('modalBody-m2')">↑ Top</button>
  </div>
</div>

<div id="modal-m3" class="modal-overlay" onclick="closeModal('modal-m3')">
  <div class="modal-container" onclick="event.stopPropagation()">
    <div class="modal-header">
      <h2>We Breath the Same Air, or Not?</h2>
      <span class="close-btn" onclick="closeModal('modal-m3')">&times;</span>
    </div>
    <div id="modalBody-m3" class="modal-body" style="max-height: 70vh;" onscroll="checkModalScroll('modalBody-m3', 'btn-m3')">
      <div class="modal-text">
        <p><i>*Contributed by Dr. An WANG*</i></p>
        <p>Disparities in air pollution exposure are traditionally mapped by linking residential addresses to static pollution data, ignoring the complex realities of human movement. We bridged this gap by fusing the highly granular mobility traces of <strong>over 500,000 anonymized users</strong> with 100-meter-resolution PM2.5 predictions in the Bronx, New York.</p>
        <figure style="margin: 2.5rem 0; text-align: left;">
          <img src="{{ site.baseurl }}/assets/research/disparity1.jpg" alt="Figure 1" style="width: 66%; height: auto; border-radius: 12px; box-shadow: 0 4px 15px rgba(18,59,93,0.1);">
          <figcaption style="font-size: 0.9rem; color: #607487; margin-top: 0.8rem; font-style: italic;">
            Figure 1: Mean exposure per street visit per income and race/ethnicity
          </figcaption>
        </figure>    
        <p>Moving beyond population-weighted averages, our trajectory-based approach tracked individualized exposure across urban micro-environments. The findings reveal that "where" exposure happens matters just as much as "how much". While overall street-level exposure is negatively correlated with income, racial and ethnic divides are far more profound. We found that people from <strong>Hispanic-majority communities</strong> suffer significantly higher PM2.5 exposure levels than any other group.</p>
        <figure style="margin: 2.5rem 0; text-align: left;">
          <img src="{{ site.baseurl }}/assets/research/disparity2.jpg" alt="Figure 2" style="width: 66%; height: auto; border-radius: 12px; box-shadow: 0 4px 15px rgba(18,59,93,0.1);">
          <figcaption style="font-size: 0.9rem; color: #607487; margin-top: 0.8rem; font-style: italic;">
            Figure 2: Exposure disparity between/within groups
          </figcaption>
        </figure>    
        <p>Crucially, our analysis demonstrates that within-group exposure variation contributes to <strong>three-quarters of the total disparity</strong>, exposing the double burden faced by vulnerable communities. These insights urge planners to move beyond generic, city-wide air quality improvements and adopt targeted, location-specific emission mitigations that actively dismantle systemic environmental injustices.</p>        
      <p><em>*Full paper is available at https://doi.org/10.1038/s44284-024-00093-x.*</em></p>
      </div>
    </div>
    <button id="btn-m3" class="modal-back-to-top" onclick="scrollModalToTop('modalBody-m3')">↑ Top</button>
  </div>
</div>

<script>
function openModal(id) {
  const modal = document.getElementById(id);
  if (modal) {
    modal.classList.add('active');
    document.body.style.overflow = "hidden";
  }
}

function closeModal(id) {
  const modal = document.getElementById(id);
  if (modal) {
    modal.classList.remove('active');
    document.body.style.overflow = "auto";
  }
}

window.addEventListener('load', () => {
  const hash = window.location.hash;
  if (hash) {
    const target = document.querySelector(hash);
    if (target) target.scrollIntoView({ behavior: 'smooth' });
  }
});
function checkModalScroll(bodyId, btnId) {
  const modalBody = document.getElementById(bodyId);
  const btn = document.getElementById(btnId);
  
  // Show button if the user scrolls down more than 150px inside the modal
  if (modalBody.scrollTop > 150) {
    btn.classList.add('show');
  } else {
    btn.classList.remove('show');
  }
}

function scrollModalToTop(bodyId) {
  const modalBody = document.getElementById(bodyId);
  modalBody.scrollTo({
    top: 0,
    behavior: 'smooth'
  });
}
</script>
