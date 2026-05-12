---
layout: page
title: "Research"
permalink: /research/
---

<p class="page-intro">
  My research focuses on the nexus of sustainable transportation systems, urban environmental sensing, and data-driven modeling. I utilize tools such as life-cycle assessment, empirical modeling, and computer vision to explore carbon-neutral pathways for metropolitan areas.
</p>

<section id="sensing" class="research-section">
  <h2>Urban Environmental Sensing</h2>
  <div class="scroll-container">
    <div class="card clickable-card" onclick="openModal('modal-s1')">
      <h3>On-road Emission Tests</h3>
      <p>Using state-of-the-art sensing for vehicle-level measurements.</p>
    </div>
    <div class="card clickable-card" onclick="openModal('modal-s2')">
      <h3>Roadside Dispersion</h3>
      <p>Characterizing pollutant dispersion and near-road air quality.</p>
    </div>
    <div class="card clickable-card" onclick="openModal('modal-s3')">
      <h3>Portable Measurements</h3>
      <p>Using PEMS at the vehicle, street, and city levels.</p>
    </div>
  </div>
</section>

<section id="energy" class="research-section">
  <h2>Transport Energy Transition</h2>
  <div class="scroll-container">
    <div class="card clickable-card" onclick="openModal('modal-e1')">
      <h3>Vehicle Electrification</h3>
      <p>Capturing uncertainty in metropolitan GHG emission inventories.</p>
    </div>
    <div class="card clickable-card" onclick="openModal('modal-e2')">
      <h3>EV Charging Impacts</h3>
      <p>Implications of charging on emissions of electricity systems.</p>
    </div>
    <div class="card clickable-card" onclick="openModal('modal-e3')">
      <h3>Automated & Electric</h3>
      <p>Effects of new technology scenarios on urban greenhouse gas emissions.</p>
    </div>
  </div>
</section>

<section id="modeling" class="research-section">
  <h2>Data-Driven Modeling</h2>
  <div class="scroll-container">
    <div class="card clickable-card" onclick="openModal('modal-m1')">
      <h3>ML for Pollution Prediction</h3>
      <p>Potential of machine learning for predicting traffic-related air pollution.</p>
    </div>
    <div class="card clickable-card" onclick="openModal('modal-m2')">
      <h3>Brake Wear Modeling</h3>
      <p>Modeling urban brake wear particle emissions in ride-hailing cases.</p>
    </div>
    <div class="card clickable-card" onclick="openModal('modal-m3')">
      <h3>Emission Inventories</h3>
      <p>Construction of multi-pollutant inventories with data-driven models.</p>
    </div>
  </div>
</section>

<div id="modal-s1" class="modal-overlay" onclick="closeModal('modal-s1')">
  <div class="modal-container" onclick="event.stopPropagation()">
    <div class="modal-header">
      <h2>On-road Vehicular Emission Tests</h2>
      <span class="close-btn" onclick="closeModal('modal-s1')">&times;</span>
    </div>
    <div class="modal-body">
      <div class="modal-text">
        <p>This work involves conducting tests using state-of-the-art sensing instrumentation, including portable emissions measurements (PEMS).</p>
      </div>
      <div class="modal-image"><div class="image-placeholder">[Project Figure]</div></div>
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
