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
        <p>Detailed description of your sensing research goes here.</p>
      </div>
      <div class="modal-image">
        <div class="image-placeholder">
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
    modal.classList.add('active'); // Matches the .active class in your SCSS
    document.body.style.overflow = "hidden";
  }
}

function closeModal(id) {
  const modal = document.getElementById(id);
  if (modal) {
    modal.classList.remove('active');
    document.body.style.overflow = "auto";
    // Clears the #theme1 from the URL without reloading the page
    history.replaceState(null, null, window.location.pathname);
  }
}

// Logic to open modal automatically based on URL hash (from Index page)
function checkHash() {
  const hash = window.location.hash;
  if (hash === "#theme1") openModal('modal1');
  if (hash === "#theme2") openModal('modal2');
  if (hash === "#theme3") openModal('modal3');
}

window.addEventListener('load', checkHash);
window.addEventListener('hashchange', checkHash);
</script>
