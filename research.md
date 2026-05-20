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
      <h3>On-road Emissions</h3>
    </div>
    <div class="card clickable-card" onclick="openModal('modal-s2')" style="background-image: url('{{ site.baseurl }}/assets/research/crowdsensing.png');">
      <h3>Crowdsourced Sensing</h3>
    </div>
    <div class="card clickable-card" onclick="openModal('modal-s3')" style="background-image: url('{{ site.baseurl }}/assets/your-image.jpg');">
      <h3>Personal Exposure Modeling</h3>
    </div>
  </div>
</section>

<section id="energy" class="research-section">
  <h2>Transport Energy Transition</h2>
  <div class="scroll-container">
    <div class="card clickable-card" onclick="openModal('modal-e1')" style="background-image: url('{{ site.baseurl }}/assets/your-image.jpg');">
      <h3>Heavy-Duty Vehicle Electrification</h3>
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
    <div class="card clickable-card" onclick="openModal('modal-m2')" style="background-image: url('{{ site.baseurl }}/assets/your-image.jpg');">
      <h3>Non-Exhaust Emissions</h3>
    </div>
    <div class="card clickable-card" onclick="openModal('modal-m3')" style="background-image: url('{{ site.baseurl }}/assets/your-image.jpg');">
      <h3>Outdoor-Indoor Continuum</h3>
    </div>
  </div>
</section>

<div id="modal-s1" class="modal-overlay" onclick="closeModal('modal-s1')">
  <div class="modal-container" onclick="event.stopPropagation()">
    <div class="modal-header">
      <h2>HK Vehicles More Polluted than Expected</h2>
      <span class="close-btn" onclick="closeModal('modal-s1')">&times;</span>
    </div>
    <div class="modal-body">
      <div class="modal-text">
        <p>Urban transportation remains a stubborn hurdle in the race toward carbon neutrality and clean air. To model city-scale traffic emissions, researchers traditionally rely on average-speed models that ignore road grade, operating under the assumption that uphill emission penalties are perfectly offset by downhill coasting. However, in mountainous metropolises like Hong Kong, this flat-road approximation falls short.</p>
  
        <p>In our recent study, we demonstrated that neglecting topography fundamentally skews our understanding of urban emissions. By fusing computer vision-based fleet classification from traffic cameras with high-resolution digital terrain models and validating the results via real-world plume-chasing measurements, we constructed a dynamic, grade-inclusive emission inventory.</p>

        <p>The results reveal a stark reality: downhill emission reductions fail to cancel out the massive fuel penalties of uphill climbs. Factoring in road grade increases Hong Kong’s citywide vehicular carbon and air pollutant estimates by <strong>10% to 30%</strong>. More critically, topography dramatically alters the spatial distribution of pollution. Over half of the city's road segments deviate by more than 10% from traditional flat-road estimates. This clusters emission hotspots in topographically complex neighborhoods with heavy-duty traffic, directly impacting local exposure.</p>

        <p>Furthermore, this high-resolution modeling exposes vulnerabilities in current climate policy. When projecting these grade-adjusted emissions, we found that Hong Kong’s ambitious 2035 transportation decarbonization target could face an approximate <strong>seven-year delay</strong> without a substantially cleaner power grid and accelerated electric vehicle adoption. For densely populated, hilly cities, these findings offer a clear directive: effective low-carbon transitions and pollution control demand that we model our urban systems in all three dimensions.</p>
      </div>
      <div class="modal-image">
        <img src="{{ site.baseurl }}/assets/hkemissions1.jpg" alt="Figure 1" style="width: 100%; border-radius: 12px; object-fit: cover; margin-bottom: 1.5rem;">
        <img src="{{ site.baseurl }}/assets/hkemissions2.jpg" alt="Figure 2" style="width: 100%; border-radius: 12px; object-fit: cover;">
      </div>
    </div>
  </div>
</div>

<div id="modal-s2" class="modal-overlay" onclick="closeModal('modal-s2')">
  <div class="modal-container" onclick="event.stopPropagation()">
    <div class="modal-header">
      <h2>Roadside Dispersion Characterization</h2>
      <span class="close-btn" onclick="closeModal('modal-s2')">&times;</span>
    </div>
    <div class="modal-body">
      <div class="modal-text">
        <p>We characterize near-road air pollution using local-scale emission and dispersion models validated against in-situ measurements.</p>
      </div>
      <div class="modal-image"><div class="image-placeholder">[Project Figure]</div></div>
    </div>
  </div>
</div>

<div id="modal-s3" class="modal-overlay" onclick="closeModal('modal-s3')">
  <div class="modal-container" onclick="event.stopPropagation()">
    <div class="modal-header">
      <h2>Portable Emissions Measurements</h2>
      <span class="close-btn" onclick="closeModal('modal-s3')">&times;</span>
    </div>
    <div class="modal-body">
      <div class="modal-text">
        <p>Study design and experiment design for emission testing at the vehicle, street, and city levels.</p>
      </div>
      <div class="modal-image"><div class="image-placeholder">[Project Figure]</div></div>
    </div>
  </div>
</div>

<div id="modal-e1" class="modal-overlay" onclick="closeModal('modal-e1')">
  <div class="modal-container" onclick="event.stopPropagation()">
    <div class="modal-header">
      <h2>Vehicle Electrification</h2>
      <span class="close-btn" onclick="closeModal('modal-e1')">&times;</span>
    </div>
    <div class="modal-body">
      <div class="modal-text">
        <p>Researching the uncertainty in emission estimates for vehicle electrification and its impact on metropolitan GHG inventories.</p>
      </div>
      <div class="modal-image"><div class="image-placeholder">[Project Figure]</div></div>
    </div>
  </div>
</div>

<div id="modal-e2" class="modal-overlay" onclick="closeModal('modal-e2')">
  <div class="modal-container" onclick="event.stopPropagation()">
    <div class="modal-header">
      <h2>Electric Vehicle Charging</h2>
      <span class="close-btn" onclick="closeModal('modal-e2')">&times;</span>
    </div>
    <div class="modal-body">
      <div class="modal-text">
        <p>Investigating marginal greenhouse gas emissions of electricity systems and the implications of EV charging patterns.</p>
      </div>
      <div class="modal-image"><div class="image-placeholder">[Project Figure]</div></div>
    </div>
  </div>
</div>

<div id="modal-e3" class="modal-overlay" onclick="closeModal('modal-e3')">
  <div class="modal-container" onclick="event.stopPropagation()">
    <div class="modal-header">
      <h2>Automated and Electric Mobility</h2>
      <span class="close-btn" onclick="closeModal('modal-e3')">&times;</span>
    </div>
    <div class="modal-body">
      <div class="modal-text">
        <p>Investigating the combined effects of automated and electric transportation on metropolitan greenhouse gas emissions.</p>
      </div>
      <div class="modal-image"><div class="image-placeholder">[Project Figure]</div></div>
    </div>
  </div>
</div>

<div id="modal-m1" class="modal-overlay" onclick="closeModal('modal-m1')">
  <div class="modal-container" onclick="event.stopPropagation()">
    <div class="modal-header">
      <h2>ML for Pollution Prediction</h2>
      <span class="close-btn" onclick="closeModal('modal-m1')">&times;</span>
    </div>
    <div class="modal-body">
      <div class="modal-text">
        <p>Evaluating the potential of machine learning models for predicting traffic-related air pollution levels.</p>
      </div>
      <div class="modal-image"><div class="image-placeholder">[Project Figure]</div></div>
    </div>
  </div>
</div>

<div id="modal-m2" class="modal-overlay" onclick="closeModal('modal-m2')">
  <div class="modal-container" onclick="event.stopPropagation()">
    <div class="modal-header">
      <h2>Brake Wear Particle Emissions</h2>
      <span class="close-btn" onclick="closeModal('modal-m2')">&times;</span>
    </div>
    <div class="modal-body">
      <div class="modal-text">
        <p>Modeling urban brake wear particle emissions using ride-hailing data as a case study.</p>
      </div>
      <div class="modal-image"><div class="image-placeholder">[Project Figure]</div></div>
    </div>
  </div>
</div>

<div id="modal-m3" class="modal-overlay" onclick="closeModal('modal-m3')">
  <div class="modal-container" onclick="event.stopPropagation()">
    <div class="modal-header">
      <h2>Multi-Pollutant Inventories</h2>
      <span class="close-btn" onclick="closeModal('modal-m3')">&times;</span>
    </div>
    <div class="modal-body">
      <div class="modal-text">
        <p>Constructing comprehensive multi-air pollutant emission inventories for urban transportation systems.</p>
      </div>
      <div class="modal-image"><div class="image-placeholder">[Project Figure]</div></div>
    </div>
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
</script>
