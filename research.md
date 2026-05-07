---
layout: page
title: "Research"
permalink: /research/
---

<div class="card-grid">
  <div class="card clickable-card" onclick="openModal('modal1')">
    <h3>Urban Environmental Sensing</h3>
    <p>Click to see details.</p>
  </div>
  </div>

<div id="modal1" class="modal-overlay" onclick="closeModal('modal1')">
  <div class="modal-container" onclick="event.stopPropagation()">
    <div class="modal-header">
      <h2>Urban Environmental Sensing</h2>
      <span class="close-btn" onclick="closeModal('modal1')">&times;</span>
    </div>
    <div class="modal-body">
      <div class="modal-text">
        <p>At S3L, we leverage sensing technologies to detect cities' undertone. This includes vehicular emission tests and roadside dispersion characterization.</p>
      </div>
      <div class="modal-image">
        <div class="image-placeholder" style="background:#f0f4f8; height:300px; border-radius:10px; display:flex; align-items:center; justify-content:center;">
          [Theme 1 Image]
        </div>
      </div>
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
    history.replaceState(null, null, window.location.pathname);
  }
}

// Automatically open modal if URL contains #themeX
function checkHash() {
  const hash = window.location.hash;
  if (hash === "#theme1") openModal('modal1');
  if (hash === "#theme2") openModal('modal2');
  if (hash === "#theme3") openModal('modal3');
}

window.addEventListener('load', checkHash);
window.addEventListener('hashchange', checkHash);
</script>
