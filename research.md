<div id="modal1" class="modal-overlay" onclick="closeModal('modal1')">
  <div class="modal-container" onclick="event.stopPropagation()">
    <div class="modal-header">
      <h2>Urban Environmental Sensing</h2>
      <span class="close-btn" onclick="closeModal('modal1')">&times;</span>
    </div>
    <div class="modal-body">
      <div class="modal-text">
        <p>At S3L, we leverage sensing technologies to detect cities' undertone. This research involves on-road vehicular emission tests and roadside emission dispersion characterization.</p>
        <h4>Key Objectives:</h4>
        <ul>
          <li>Development of portable emission measurement systems.</li>
          <li>Mapping city-level pollutant concentrations.</li>
        </ul>
      </div>
      <div class="modal-image">
        <div class="image-placeholder">[Image: Urban Sensing Setup]</div>
      </div>
    </div>
  </div>
</div>

<script>
function openModal(id) {
  const modal = document.getElementById(id);
  modal.classList.add('active');
  document.body.style.overflow = "hidden";
}

function closeModal(id) {
  const modal = document.getElementById(id);
  modal.classList.remove('active');
  document.body.style.overflow = "auto";
  // Clean URL hash without reloading
  history.replaceState(null, null, ' ');
}

// Auto-open logic from Home Page links
window.addEventListener('hashchange', () => {
  const hash = window.location.hash.substring(1);
  if(hash.startsWith('theme')) openModal('modal' + hash.slice(-1));
});

window.addEventListener('load', () => {
  const hash = window.location.hash.substring(1);
  if(hash.startsWith('theme')) openModal('modal' + hash.slice(-1));
});
</script>
