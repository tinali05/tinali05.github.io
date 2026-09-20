---
layout: default
title: Tina Li
---

# About Me

<div class="about-section">
  <div class="about-photo">
    <img src="assets/headshot.JPEG" alt="Tina Li headshot">
  </div>

  <div class="about-text">
    <p>
      I am a driven and curious undergraduate student at Cornell University studying Operations Research and Information Engineering (ORIE)       and Computer Science with an expected graduation of December 2026. I am passionate about translating data into actionable insights,         as well as the intersection between data analytics and finance.
    </p>

    <p>
      If you asked the people closest to me, they would describe me as “their biggest hypeman.” I pride myself on showing genuine care            toward the people I work with and being a dependable person who’s always true to their word. Whether that means celebrating a               friend’s successes, or stepping up when no one else in the team can, I try to be someone others know they can count on.
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
    <img class="zoomable" src="assets/emmissions.png" alt="CO2 Emissions Analysis">
    <h3>Vehicle CO2 Emissions Analysis</h3>
    <p>Exploratory data analysis to determine key predictors of vehicle CO2 emissions.</p>
  </div>

  <div class="project-card">
    <img class="zoomable" src="assets/camlchef.png" alt="CamlChef">
    <h3>CamlChef</h3>
    <p>Interactive cooking game with customization and tracking features, coded using OCaml.</p>
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

- [LinkedIn](https://www.linkedin.com/in/tina-m-li/)
- [GitHub](https://github.com/tml228)
- [Email](mailto:tinamyli@live.com)
