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
    <div class="card clickable-card" onclick="openModal('modal-s1')" style="background-image: url('{{ site.baseurl }}/assets/research/onroademissions.jpg');">
      <h3>Plume Chasing</h3>
    </div>
    <div class="card clickable-card" onclick="openModal('modal-s2')" style="background-image: url('{{ site.baseurl }}/assets/research/crowdsensing.png');">
      <h3>Crowdsourced Sensing</h3>
    </div>
    <div class="card clickable-card" onclick="openModal('modal-s3')" style="background-image: url('{{ site.baseurl }}/assets/your-image.jpg');">
      <h3>Multimodal Exposure Modeling</h3>
    </div>
  </div>
</section>

<section id="energy" class="research-section">
  <h2>Transport Energy Transition</h2>
  <div class="scroll-container">
    <div class="card clickable-card" onclick="openModal('modal-e1')" style="background-image: url('{{ site.baseurl }}/assets/onroademissions.jpg');">
      <h3>On-Road Emission Inventory</h3>
    </div>
    <div class="card clickable-card" onclick="openModal('modal-e2')" style="background-image: url('{{ site.baseurl }}/assets/your-image.jpg');">
      <h3>Hard-to-Abate Modes</h3>
    </div>
    <div class="card clickable-card" onclick="openModal('modal-e3')" style="background-image: url('{{ site.baseurl }}/assets/your-image.jpg');">
      <h3>Uncertainties in Transition</h3>
    </div>
  </div>
</section>

<section id="modeling" class="research-section">
  <h2>Data-Driven Modeling</h2>
  <div class="scroll-container">
    <div class="card clickable-card" onclick="openModal('modal-m1')" style="background-image: url('{{ site.baseurl }}/assets/your-image.jpg');">
      <h3>Spatial & Temporal Imputation </h3>
    </div>
    <div class="card clickable-card" onclick="openModal('modal-m2')" style="background-image: url('{{ site.baseurl }}/assets/IOcontinuum.png');">
      <h3>Outdoor-Indoor Continuum</h3>
    </div>
    <div class="card clickable-card" onclick="openModal('modal-m3')" style="background-image: url('{{ site.baseurl }}/assets/your-image.jpg');">
      <h3>Non-Exhaust Emissions</h3>
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
        <p>*Contributed by Dr. Zeyu ZHANG*</p>
        <p>Urban air quality suffers disproportionately from a fraction of heavy-duty diesel vehicles (HDDVs). Existing regulations rely on lab tests that fail to capture real-world, high-emitting behaviors. We deployed a mobile plume-chasing platform equipped with fast-response gas analyzers across Hong Kong to test HDDVs in their natural environment.</p>
        
        <figure style="margin: 2.5rem 0; text-align: left;">
          <img src="{{ site.baseurl }}/assets/research/plumechasing1.jpg" alt="Figure 1" style="width: 66%; height: auto; border-radius: 12px; box-shadow: 0 4px 15px rgba(18,59,93,0.1);">
          <figcaption style="font-size: 0.9rem; color: #607487; margin-top: 0.8rem; font-style: italic;">
            Figure 1: Plume chasing instrumentation setup
          </figcaption>
        </figure>
        
        <p>By translating fuel-based measurements into distance- and power-based emission factors, we found that NOX emissions are highly sensitive to road grade and routinely exceed regulatory baselines by over twofold. Shockingly, around 10% of light goods vehicles and 22% of heavy goods vehicles emit NOX at more than double the Euro IV limits. Removing these "super-emitters"—who represent just 14% of the fleet—could slash goods-vehicle NOX emissions by 31%.</p>        
        <figure style="margin: 2.5rem 0; text-align: left;">
          <img src="{{ site.baseurl }}/assets/research/plumechasing2.jpg" alt="Figure 2" style="width: 66%; height: auto; border-radius: 12px; box-shadow: 0 4px 15px rgba(18,59,93,0.1);">
          <figcaption style="font-size: 0.9rem; color: #607487; margin-top: 0.8rem; font-style: italic;">
            Figure 2: Observed emission standard compliance in heavy-duty(above) and light-duty(below) trucks 
          </figcaption>
        </figure>        
        
        <p>This work highlights mobile plume-chasing as a highly cost-effective, scalable tool for screening high-emitting vehicles and enforcing environmental compliance in dense, mountainous cities.</p>        
        <p><em>*Full paper is available at https://doi.org/10.1016/j.trd.2026.105270.*</em></p>
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
        <p>*Contributed by Wenyu WANG*</p>
        <p>The democratization of air quality monitoring through low-cost sensor (LCS) networks promises unprecedented, block-by-block visibility into urban pollution. Yet, poor data reliability has largely relegated these networks to citizen science rather than rigorous policymaking. Traditional calibration requires physically co-locating sensors with "gold standard" reference stations—an unscalable bottleneck.</p>
        <figure style="margin: 2.5rem 0; text-align: left;">
          <img src="{{ site.baseurl }}/assets/research/remocalib1.png" alt="Figure 1" style="width: 66%; height: auto; border-radius: 12px; box-shadow: 0 4px 15px rgba(18,59,93,0.1);">
          <figcaption style="font-size: 0.9rem; color: #607487; margin-top: 0.8rem; font-style: italic;">
            Figure 1: The remote calibration concept
          </figcaption>
        </figure>  
        <p>We developed a novel <strong>"remote calibration"</strong> framework that eliminates the need for physical collocation. By matching <strong>over 33 million hourly observations</strong> from the largest US LCS network against reference stations during periods of low regional PM2.5 variability, we generated metropolis-specific calibration models. This approach successfully corrected systematic sensor biases across the ten largest US metropolitan areas.</p>
        <figure style="margin: 2.5rem 0; text-align: left;">
          <img src="{{ site.baseurl }}/assets/research/remocalib2.png" alt="Figure 1" style="width: 66%; height: auto; border-radius: 12px; box-shadow: 0 4px 15px rgba(18,59,93,0.1);">
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
        <p>*Contributed by Xiaotong ZHANG*</p>
        <p>Study design and experiment design for emission testing at the vehicle, street, and city levels.</p>
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
        <p>*Contributed by Dr. Zeyu ZHANG*</p>
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
    <button id="btn-e1" class="modal-back-to-top" onclick="scrollModalToTop('modalBody-e1')">↑ Top</button>
  </div>
</div>

<div id="modal-e2" class="modal-overlay" onclick="closeModal('modal-e2')">
  <div class="modal-container" onclick="event.stopPropagation()">
    <div class="modal-header">
      <h2>Electric Vehicle Charging</h2>
      <span class="close-btn" onclick="closeModal('modal-e2')">&times;</span>
    </div>
    <div id="modalBody-e2" class="modal-body" style="max-height: 70vh;" onscroll="checkModalScroll('modalBody-e2', 'btn-e2')">
      <div class="modal-text">
        <p>Investigating marginal greenhouse gas emissions of electricity systems and the implications of EV charging patterns.</p>
        </div>
    </div>
    <button id="btn-e2" class="modal-back-to-top" onclick="scrollModalToTop('modalBody-e2')">↑ Top</button>
  </div>
</div>

<div id="modal-e3" class="modal-overlay" onclick="closeModal('modal-e3')">
  <div class="modal-container" onclick="event.stopPropagation()">
    <div class="modal-header">
      <h2>Automated and Electric Mobility</h2>
      <span class="close-btn" onclick="closeModal('modal-e3')">&times;</span>
    </div>
    <div id="modalBody-e3" class="modal-body" style="max-height: 70vh;" onscroll="checkModalScroll('modalBody-e3', 'btn-e3')">
      <div class="modal-text">
        <p>Investigating the combined effects of automated and electric transportation on metropolitan greenhouse gas emissions.</p>
        </div>
    </div>
    <button id="btn-e3" class="modal-back-to-top" onclick="scrollModalToTop('modalBody-e3')">↑ Top</button>
  </div>
</div>

<div id="modal-m1" class="modal-overlay" onclick="closeModal('modal-m1')">
  <div class="modal-container" onclick="event.stopPropagation()">
    <div class="modal-header">
      <h2>ML for Pollution Prediction</h2>
      <span class="close-btn" onclick="closeModal('modal-m1')">&times;</span>
    </div>
    <div id="modalBody-m1" class="modal-body" style="max-height: 70vh;" onscroll="checkModalScroll('modalBody-m1', 'btn-m1')">
      <div class="modal-text">
        <p>Evaluating the potential of machine learning models for predicting traffic-related air pollution levels.</p>
        </div>
    </div>
    <button id="btn-m1" class="modal-back-to-top" onclick="scrollModalToTop('modalBody-m1')">↑ Top</button>
  </div>
</div>

<div id="modal-m2" class="modal-overlay" onclick="closeModal('modal-m2')">
  <div class="modal-container" onclick="event.stopPropagation()">
    <div class="modal-header">
      <h2></h2>
      <span class="close-btn" onclick="closeModal('modal-m2')">&times;</span>
    </div>
    <div id="modalBody-m2" class="modal-body" style="max-height: 70vh;" onscroll="checkModalScroll('modalBody-m2', 'btn-m2')">
      <div class="modal-text">
        <p>Modeling urban brake wear particle emissions using ride-hailing data as a case study.</p>
        </div>
    </div>
    <button id="btn-m2" class="modal-back-to-top" onclick="scrollModalToTop('modalBody-m2')">↑ Top</button>
  </div>
</div>

<div id="modal-m3" class="modal-overlay" onclick="closeModal('modal-m3')">
  <div class="modal-container" onclick="event.stopPropagation()">
    <div class="modal-header">
      <h2></h2>
      <span class="close-btn" onclick="closeModal('modal-m3')">&times;</span>
    </div>
    <div id="modalBody-m3" class="modal-body" style="max-height: 70vh;" onscroll="checkModalScroll('modalBody-m3', 'btn-m3')">
      <div class="modal-text">
        <p>Constructing comprehensive multi-air pollutant emission inventories for urban transportation systems.</p>
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
