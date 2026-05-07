---
layout: page
title: "Research"
permalink: /research/
---

My research focuses on sustainable transportation systems, urban environmental sensing, and data-driven modeling.

<div class="card-grid">
  <div class="card clickable-card" onclick="openModal('modal1')">
    <div class="card-image-placeholder">
          </div>
    <h3>Urban Environmental Sensing</h3>
    <p>Using advanced sensors to detect cities' undertone. Click to learn more.</p>
  </div>

  <div class="card clickable-card" onclick="openModal('modal2')">
    <div class="card-image-placeholder">
          </div>
    <h3>Transport Energy Transition</h3>
    <p>Exploring equitable pathways for carbon-neutral transitions. Click to learn more.</p>
  </div>

  <div class="card clickable-card" onclick="openModal('modal3')">
    <div class="card-image-placeholder">
          </div>
    <h3>Data-Driven Modeling</h3>
    <p>Fusing crowd-sourced big datasets for urban system modeling. Click to learn more.</p>
  </div>
</div>

<div id="modal1" class="modal-overlay" onclick="closeModal('modal1')">
  <div class="modal-content" onclick="event.stopPropagation()">
    <span class="close-btn" onclick="closeModal('modal1')">&times;</span>
    <h2>Urban Environmental Sensing</h2>
    <p>This work involves on-road vehicular emission tests using state-of-the-art sensing instrumentation. We focus on roadside emission dispersion characterization and portable emissions measurements at the vehicle, street, and city levels.</p>
  </div>
</div>

<div id="modal2" class="modal-overlay" onclick="closeModal('modal2')">
  <div class="modal-content" onclick="event.stopPropagation()">
    <span class="close-btn" onclick="closeModal('modal2')">&times;</span>
    <h2>Transport Energy Transition</h2>
    <p>We investigate the effects of vehicle electrification on metropolitan greenhouse gas emission inventories. This includes evaluating the implications of electric vehicle charging on electricity systems.</p>
  </div>
</div>

<div id="modal3" class="modal-overlay" onclick="closeModal('modal3')">
  <div class="modal-content" onclick="event.stopPropagation()">
    <span class="close-btn" onclick="closeModal('modal3')">&times;</span>
    <h2>Data-Driven Modeling</h2>
    <p>We utilize machine learning and empirical modeling to predict traffic-related air pollution and construct multi-pollutant emission inventories.</p>
  </div>
</div>

<script>
function openModal(id) {
  document.getElementById(id).style.display = "flex";
  document.body.style.overflow = "hidden"; // Prevent scrolling
}
function closeModal(id) {
  document.getElementById(id).style.display = "none";
  document.body.style.overflow = "auto";
}

## Full Publication List

For a complete and updated publication list, please also see:

- [Google Scholar](#)
- [ORCID](#)
- [DBLP](#)
- [PolyU Profile](#)

### Journal Articles

1. **[Paper Title 1]**  
   [Authors]  
   *[Journal Name]*, [Year].

2. **[Paper Title 2]**  
   [Authors]  
   *[Journal Name]*, [Year].

3. **[Paper Title 3]**  
   [Authors]  
   *[Journal Name]*, [Year].

### Conference Papers

1. **[Paper Title 1]**  
   [Authors]  
   In *Proceedings of [Conference Name]*, [Year].

2. **[Paper Title 2]**  
   [Authors]  
   In *Proceedings of [Conference Name]*, [Year].

3. **[Paper Title 3]**  
   [Authors]  
   In *Proceedings of [Conference Name]*, [Year].
