---
layout: page
title: Poster gallery
permalink: /poster/
---
# Posters
<div class="poster-gallery">

  <div class="poster-item">
    <img src="/assets/posters/77_CGourves_NonTransiting.jpg" alt="Exobiologie Jeunes Chercheurs et Chercheuses 2024" onclick="openLightbox(this.src)">
    <p class="poster-caption">Exobiologie Jeunes Chercheurs et Chercheuses 2024
      <a href="/assets/posters/PosterEJC24.pdf" target="_blank">(PDF)</a>
    </p>
  </div>

  <div class="poster-item">
    <img src="/assets/posters/77_CGourves_NonTransiting.jpg" alt="European Geosciences Union 2025" onclick="openLightbox(this.src)">
    <p class="poster-caption">European Geosciences Union 2025
      <a href="/assets/posters/PosterEGU.pdf" target="_blank">(PDF)</a>
    </p>
  </div>

  <div class="poster-item">
    <img src="/assets/posters/77_CGourves_NonTransiting.jpg" alt="École des Houches - Planetary Atmospheres and Interiors: A Two-Way Connection" onclick="openLightbox(this.src)">
    <p class="poster-caption">École des Houches - Planetary Atmospheres and Interiors: A Two-Way Connection
      <a href="/assets/posters/PosterHouches26.pdf" target="_blank">(PDF)</a>
    </p>
  </div>

  <div class="poster-item">
    <img src="/assets/posters/77_CGourves_NonTransiting.jpg" alt="Ariel Open Science Conference 2026" onclick="openLightbox(this.src)">
    <p class="poster-caption">Ariel Open Science Conference 2026
      <a href="/assets/posters/77_CGourves_NonTransiting.pdf" target="_blank">(PDF)</a>
    </p>
  </div>

  <div class="poster-item">
    <img src="/assets/posters/77_CGourves_NonTransiting.jpg" alt="Cool Stars 23" onclick="openLightbox(this.src)">
    <p class="poster-caption">Cool Stars 23
      <a href="/assets/posters/P2081_Gourves.pdf" target="_blank">(PDF)</a>
    </p>
  </div>

</div>

<!-- Lightbox overlay -->
<div id="lightbox" class="lightbox" onclick="closeLightbox()">
  <span class="lightbox-close" onclick="closeLightbox()">&times;</span>
  <img class="lightbox-content" id="lightbox-img" alt="">
</div>

<script>
function openLightbox(src) {
  document.getElementById('lightbox-img').src = src;
  document.getElementById('lightbox').style.display = "flex";
}
function closeLightbox() {
  document.getElementById('lightbox').style.display = "none";
  document.getElementById('lightbox-img').src = "";
}
document.addEventListener('keydown', function(e) {
  if (e.key === "Escape") closeLightbox();
});
</script>
