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
      <p>Click for project brief.</p>
    </div>
    <div class="card clickable-card" onclick="openModal('modal-s2')">
      <h3>Dispersion Characterization</h3>
      <p>Click for project brief.</p>
    </div>
    <div class="card clickable-card" onclick="openModal('modal-s3')">
      <h3>Low-cost Sensor Networks</h3>
      <p>Click for project brief.</p>
    </div>
  </div>
</section>

<section id="energy" class="research-section">
  <h2>Transport Energy Transition</h2>
  <div class="scroll-container">
    <div class="card clickable-card" onclick="openModal('modal-e1')">
      <h3>Electrification Impact</h3>
      <p>Click for project brief.</p>
    </div>
    <div class="card clickable-card" onclick="openModal('modal-e2')">
      <h3>Charging Infrastructure</h3>
      <p>Click for project brief.</p>
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
        <p>Detailed brief regarding emission instrumentation and city-level testing.</p>
      </div>
      <div class="modal-image"><div class="image-placeholder">[Project Image]</div></div>
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

// Handle auto-scroll from Index page
window.addEventListener('load', () => {
  const hash = window.location.hash;
  if (hash) {
    const target = document.querySelector(hash);
    if (target) target.scrollIntoView({ behavior: 'smooth' });
  }
});
</script>
