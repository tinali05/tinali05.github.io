---
layout: default
title: Tina Li
---

# Tina Li

ORIE student at Cornell University.

## About Me

<div class="about-section">
  <div class="about-photo">
    <img src="assets/headshot.JPEG" alt="Tina Li headshot">
  </div>

  <div class="about-text">
    <p>
      I am an Operations Research and Information Engineering student at Cornell University
      interested in data science, analytics, optimization, and engineering for social impact.
    </p>

    <p>
      I have experience in portfolio risk analysis, location-routing optimization, and
      infrastructure-focused engineering work through Cornell Engineers in Action.
    </p>
  </div>
</div>

## Experience
- Cboe Regulatory Intern (Incoming)
- Cornell Engineers in Action
- CBS Routing & Optimization Research

## Projects

<div class="projects-grid">

  <div class="project-card">
    <img class="zoomable" src="assets/portfolio-risk-scanner.png" alt="PortfolioRiskScanner">
    <h3>PortfolioRiskScanner</h3>
    <p>Risk-focused stock recommendation system using TF-IDF, SVD, sentiment, and news-based risk signals.</p>
  </div>

  <div class="project-card">
    <img class="zoomable" src="assets/cbs-routing.png" alt="CBS Location-Routing Research">
    <h3>CBS Location-Routing Research</h3>
    <p>Optimized facility locations and vehicle routes for container-based sanitation implementation in Kisumu, Kenya.</p>
  </div>

  <div class="project-card">
    <img class="zoomable" src="assets/eia.png" alt="Engineers in Action">
    <h3>Engineers in Action</h3>
    <p>Infrastructure-focused engineering work supporting pedestrian bridges and WASH systems in Eswatini.</p>
  </div>

</div>

<div id="image-modal" class="modal">
  <span id="modal-close">&times;</span>
  <img id="modal-image" class="modal-content">
</div>

<script>
window.addEventListener("load", function () {
  const modal = document.getElementById("image-modal");
  const modalImage = document.getElementById("modal-image");
  const closeButton = document.getElementById("modal-close");

  document.querySelectorAll(".zoomable").forEach(function (img) {
    img.addEventListener("click", function () {
      modal.style.display = "block";
      modalImage.src = img.src;
    });
  });

  closeButton.addEventListener("click", function () {
    modal.style.display = "none";
  });

  modal.addEventListener("click", function (event) {
    if (event.target === modal) {
      modal.style.display = "none";
    }
  });
});
</script>

## Contact
- LinkedIn
- GitHub
- Email
