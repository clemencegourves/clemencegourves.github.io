---
layout: page
title: Poster gallery
permalink: /poster/
---
# Posters
<div class="poster-gallery">

  <div class="poster-item">
    <img src="/assets/poster/P2081_Gourves.jpg" alt="Cool Stars 23" onclick="openLightbox(this.src)">
    <div class="poster-info">
      <p class="poster-authors">C. Gourv&egrave;s, A. Strugarek &amp; A. Paul &ndash; <em>Cool Stars 23</em></p>
      <p class="poster-title">Complex stellar magnetism and realistic star-planet magnetic interactions
        <a href="http://zenodo.org/records/20593722" target="_blank">(PDF)</a>
      </p>
      <p class="poster-location">Tokyo, Japan &ndash; June 2026</p>
    </div>
  </div>
  
  <div class="poster-item">
    <img src="/assets/poster/77_CGourves_NonTransiting.jpg" alt="Ariel Open Science Conference 2026" onclick="openLightbox(this.src)">
    <div class="poster-info">
      <p class="poster-authors">C. Gourv&egrave;s, S.N. Breton, A. Dyrek, et al. &ndash; <em>Ariel Open Science Conference 2026</em></p>
      <p class="poster-title">Detection and characterisation of non-transiting exoplanets with orbital brightness modulation
        <a href="https://drive.google.com/file/d/1LD1ghURn0ellnKCrMowrCkVv54deqzyX/view?usp=drive_link" target="_blank">(PDF)</a>
      </p>
      <p class="poster-location">ECSAT, Didcot, United Kingdom &ndash; March 2026</p>
    </div>
  </div>

  <div class="poster-item">
    <img src="/assets/poster/PosterHouches26.jpg" alt="École des Houches" onclick="openLightbox(this.src)">
    <div class="poster-info">
      <p class="poster-authors">C. Gourv&egrave;s, A. Strugarek &amp; A. Paul &ndash; <em>&Eacute;cole des Houches &ndash; Planetary Atmospheres and Interiors: A Two-Way Connection</em></p>
      <p class="poster-title">Global star&ndash;hot Jupiter magnetic interactions: implications for upper atmosphere heating
        <a href="https://drive.google.com/file/d/1wVHZgSmgz6ZWpVYvHt79rgLVLUUPT3BD/view?usp=drive_link" target="_blank">(PDF)</a>
      </p>
      <p class="poster-location">Les Houches, France &ndash; February 2026</p>
    </div>
  </div>

  <div class="poster-item">
    <img src="/assets/poster/PosterEGU.jpg" alt="EGU General Assembly 2025" onclick="openLightbox(this.src)">
    <div class="poster-info">
      <p class="poster-authors">C. Gourv&egrave;s &amp; A. Strugarek &ndash; <em>EGU General Assembly 2025</em></p>
      <p class="poster-title">The role of magnetic coupling in exoplanet atmospheres: insights from star-planet magnetic interactions
        <a href="https://ui.adsabs.harvard.edu/link_gateway/2025EGUGA..27.2525G/doi:10.5194/egusphere-egu25-2525" target="_blank">(DOI)</a>
        <a href="https://drive.google.com/file/d/1IxeDeyNQtisGMX9Tc8em3U8h5yZuavTd/view?usp=sharing" target="_blank">(PDF)</a>
      </p>
      <p class="poster-location">Vienna, Austria &ndash; April 2025</p>
    </div>
  </div>

  <div class="poster-item">
    <img src="/assets/poster/PosterEJC24.jpg" alt="Exobiologie Jeunes Chercheur·ses 2024" onclick="openLightbox(this.src)">
    <div class="poster-info">
      <p class="poster-authors">C. Gourv&egrave;s &amp; A. Strugarek &ndash; <em>Exobiologie Jeunes Chercheur&middot;ses 2024</em></p>
      <p class="poster-title">A key hidden factor behind planetary habitability: how to characterise exoplanetary magnetic field?
        <a href="https://drive.google.com/file/d/1U3zr38j5EGuag-vZD37dctptc4SYTavQ/view?usp=drive_link" target="_blank">(PDF)</a>
      </p>
      <p class="poster-location">Paris, France &ndash; November 2024</p>
    </div>
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
