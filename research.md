---
layout: page
title: "Research"
permalink: /research/
---

<section id="sensing" class="research-section">
  <h2>Urban Environmental Sensing</h2>
  <div class="scroll-container">
    <div class="card clickable-card" onclick="openModal('modal-s1')">
      <h3>On-road Emission Tests</h3>
      <p>Brief description of testing methods. Click to learn more.</p>
    </div>
    <div class="card clickable-card" onclick="openModal('modal-s2')">
      <h3>Roadside Dispersion</h3>
      <p>Characterizing pollutant spread. Click to learn more.</p>
    </div>
    <div class="card clickable-card" onclick="openModal('modal-s3')">
      <h3>Portable Measurements</h3>
      <p>Using PEMS at the street level. Click to learn more.</p>
    </div>
  </div>
</section>

<section id="energy" class="research-section">
  <h2>Transport Energy Transition</h2>
  <div class="scroll-container">
    <div class="card clickable-card" onclick="openModal('modal-e1')">
      <h3>Vehicle Electrification</h3>
      <p>Metropolitan GHG inventory impacts. Click to learn more.</p>
    </div>
    <div class="card clickable-card" onclick="openModal('modal-e2')">
      <h3>Charging Infrastructure</h3>
      <p>Evaluating grid implications. Click to learn more.</p>
    </div>
    <div class="card clickable-card" onclick="openModal('modal-e3')">
      <h3>Carbon-neutral Pathways</h3>
      <p>Equitable transition strategies. Click to learn more.</p>
    </div>
  </div>
</section>

<section id="modeling" class="research-section">
  <h2>Data-Driven Modeling</h2>
  <div class="scroll-container">
    <div class="card clickable-card" onclick="openModal('modal-m1')">
      <h3>Big Data Fusion</h3>
      <p>Modeling urban systems with crowd-sourced data. Click to learn more.</p>
    </div>
    <div class="card clickable-card" onclick="openModal('modal-m2')">
      <h3>Traffic Air Pollution</h3>
      <p>Empirical modeling and prediction. Click to learn more.</p>
    </div>
    <div class="card clickable-card" onclick="openModal('modal-m3')">
      <h3>Emission Inventories</h3>
      <p>Constructing multi-pollutant datasets. Click to learn more.</p>
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
        <p>This project utilizes state-of-the-art sensing instrumentation to measure emissions at the vehicle level across different city environments.</p>
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

// Redirect and scroll logic from Home Page
window.addEventListener('load', () => {
  const hash = window.location.hash;
  if (hash) {
    const target = document.querySelector(hash);
    if (target) target.scrollIntoView({ behavior: 'smooth' });
  }
});
</script>
