---
layout: archive
title: "Lab Members"
permalink: /lab-members/
author_profile: false
redirect_from:
  - /lab
  - /people
  - /team
---

{% include base_path %}

<style>
body {
  background-image: linear-gradient(rgba(255,255,255,0.76), rgba(255,255,255,0.76)), url('/images/MedBowPeak.jpg');
  background-size: cover;
  background-position: center;
  background-attachment: fixed;
}
.masthead {
  background: transparent !important;
  border-bottom: none !important;
  box-shadow: none !important;
}
.greedy-nav { background: transparent !important; }

.hes-member-card {
  display: flex;
  gap: 2em;
  align-items: flex-start;
  padding: 1.6em;
  background: #f8f8f8;
  border-radius: 6px;
  margin-bottom: 1.8em;
}
@media (max-width: 600px) {
  .hes-member-card { flex-direction: column; align-items: center; text-align: center; }
}
.hes-member-card__avatar {
  width: 130px;
  height: 130px;
  border-radius: 50%;
  object-fit: cover;
  flex-shrink: 0;
}
.hes-member-card__name {
  margin-top: 0;
  margin-bottom: 0.2em;
  font-size: 1.1rem;
  font-weight: 700;
}
.hes-member-card__title {
  margin: 0 0 0.7em;
  color: #555;
  font-size: 0.85rem;
  line-height: 1.5;
}
.hes-member-card__bio {
  margin: 0 0 0.8em;
  font-size: 0.88rem;
  line-height: 1.75;
  color: #333;
}
.hes-member-card__pub {
  font-size: 0.82rem;
  color: #444;
  border-left: 3px solid #2a6e49;
  padding-left: 0.75em;
  margin: 0 0 0.9em;
  line-height: 1.55;
}
.hes-member-card__links {
  display: flex;
  flex-wrap: wrap;
  gap: 0.6em;
  font-size: 0.83rem;
}
.hes-member-card__links a {
  color: #2a6e49;
  text-decoration: none;
}
.hes-member-card__links a:hover { text-decoration: underline; }
.hes-members-heading {
  font-size: 1.2rem;
  font-weight: 700;
  border-bottom: 2px solid #f0f0f0;
  padding-bottom: 0.4em;
  margin: 2.2em 0 1.3em;
}
.hes-avatar-placeholder {
  width: 130px;
  height: 130px;
  border-radius: 50%;
  flex-shrink: 0;
  background: #d4e9de;
  color: #2a6e49;
  display: flex;
  align-items: center;
  justify-content: center;
  font-weight: 700;
  font-size: 2rem;
  letter-spacing: -0.04em;
}
/* CV buttons */
.hes-cv-btn {
  display: inline-flex;
  align-items: center;
  gap: 0.3em;
  padding: 0.22em 0.6em;
  border-radius: 4px;
  font-size: 0.8rem;
  font-weight: 600;
  text-decoration: none !important;
  transition: background 0.15s;
}
.hes-cv-btn--view {
  background: #2a6e49;
  color: #fff !important;
}
.hes-cv-btn--view:hover { background: #1e5237; }
.hes-cv-btn--download {
  background: transparent;
  color: #2a6e49 !important;
  border: 1.5px solid #2a6e49;
}
.hes-cv-btn--download:hover { background: #edf6f1; }
/* CV modal */
.hes-cv-modal {
  display: none;
  position: fixed;
  inset: 0;
  z-index: 9999;
  background: rgba(0,0,0,0.65);
  align-items: center;
  justify-content: center;
}
.hes-cv-modal.is-open { display: flex; }
.hes-cv-modal__box {
  background: #fff;
  border-radius: 8px;
  width: min(92vw, 860px);
  height: min(92vh, 1100px);
  display: flex;
  flex-direction: column;
  overflow: hidden;
  box-shadow: 0 8px 40px rgba(0,0,0,0.35);
}
.hes-cv-modal__header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0.75em 1.1em;
  border-bottom: 1px solid #e8e8e8;
  flex-shrink: 0;
}
.hes-cv-modal__title {
  font-weight: 700;
  font-size: 0.95rem;
  color: #222;
}
.hes-cv-modal__actions {
  display: flex;
  align-items: center;
  gap: 0.75em;
}
.hes-cv-modal__download {
  font-size: 0.8rem;
  color: #2a6e49;
  text-decoration: none;
  font-weight: 600;
}
.hes-cv-modal__download:hover { text-decoration: underline; }
.hes-cv-modal__close {
  background: none;
  border: none;
  font-size: 1.5rem;
  cursor: pointer;
  color: #666;
  line-height: 1;
  padding: 0.1em 0.3em;
}
.hes-cv-modal__close:hover { color: #222; }
.hes-cv-modal__iframe {
  flex: 1;
  width: 100%;
  border: none;
}
</style>

<h2 class="hes-members-heading">Principal Investigator</h2>

<div class="hes-member-card">
  <img class="hes-member-card__avatar" src="/images/profile.jpg" alt="Jake Hawes">
  <div>
    <div class="hes-member-card__name">Jason 'Jake' Hawes</div>
    <p class="hes-member-card__title">Assistant Professor, School of Computing &amp; Haub School of Environment and Natural Resources<br>University of Wyoming &mdash; Laramie, WY</p>
    <p class="hes-member-card__bio">Jake's research deploys mixed methods and interdisciplinary analysis to model coupled natural-human systems across scales. His recent and ongoing work includes exploring the relationship between natural hazards and community adaptive capacity, understanding the role of urban agriculture in future cities via industrial ecology and spatial science, and improving models of infrastructure system resilience.</p>
    <div class="hes-member-card__links">
      {% if site.author.email %}<a href="mailto:{{ site.author.email }}">&#9993; {{ site.author.email }}</a>{% endif %}
      {% if site.author.googlescholar %}<a href="{{ site.author.googlescholar }}" target="_blank">Google Scholar</a>{% endif %}
      {% if site.author.orcid %}<a href="{{ site.author.orcid }}" target="_blank">ORCID</a>{% endif %}
      {% if site.author.researchgate %}<a href="{{ site.author.researchgate }}" target="_blank">ResearchGate</a>{% endif %}
      {% if site.author.linkedin %}<a href="https://www.linkedin.com/in/{{ site.author.linkedin }}" target="_blank">LinkedIn</a>{% endif %}
      {% if site.author.github %}<a href="https://github.com/{{ site.author.github }}" target="_blank">GitHub</a>{% endif %}
      <a href="#" class="hes-cv-btn hes-cv-btn--view" data-cv-view="/files/hawes_cv.pdf" data-cv-name="Jake Hawes">&#128196; View CV</a>
      <a href="/files/hawes_cv.pdf" download class="hes-cv-btn hes-cv-btn--download">&#11015; Download CV</a>
    </div>
  </div>
</div>

<h2 class="hes-members-heading">Current Lab Members</h2>

<!-- Vanessa Lueck -->
<div class="hes-member-card">
  <div class="hes-avatar-placeholder" aria-label="Vanessa Lueck">VL</div>
  <div>
    <div class="hes-member-card__name">Vanessa Lueck, PhD</div>
    <p class="hes-member-card__title">Postdoctoral Research Associate<br>University of Wyoming &mdash; Laramie, WY</p>
    <p class="hes-member-card__bio">Vanessa works on natural/critical infrastructure, natural resource management (primarily water), hazard and risk governance, rural resilience, system modeling, community-based participatory research and innovative solutions. She recently moved from the Pacific Institute for Climate Solutions where she worked on the Living with Water project. In the Living with Water project, she focused on the role of values and Indigenous knowledges, nature-based solutions, and innovative governance solutions to drive local sustainable coastal climate adaptation processes. She has been active in governance and sustainability at all scales ranging from local health care policy implementation to international climate change conferences and marine awareness for the maritime industry.</p>
    <div class="hes-member-card__pub">Lueck, V., Lokman, K., Low, M., &amp; Doyon, A. (2026). The value of values: Rethinking flood adaptation practices. <em>Environmental Science &amp; Policy</em>, 179, 104385.</div>
    <div class="hes-member-card__links">
      <a href="mailto:vlueck@uwyo.edu">&#9993; vlueck@uwyo.edu</a>
      <!-- CV: upload /files/lueck_cv.pdf then uncomment:
      <a href="#" class="hes-cv-btn hes-cv-btn--view" data-cv-view="/files/lueck_cv.pdf" data-cv-name="Vanessa Lueck">&#128196; View CV</a>
      <a href="/files/lueck_cv.pdf" download class="hes-cv-btn hes-cv-btn--download">&#11015; Download CV</a>
      -->
    </div>
  </div>
</div>

<!-- Md. Ismail Hossain -->
<div class="hes-member-card">
  <img class="hes-member-card__avatar" src="/images/Ismail_Hossain.jpeg" alt="Md. Ismail Hossain">
  <div>
    <div class="hes-member-card__name">Md. Ismail Hossain</div>
    <p class="hes-member-card__title">Graduate Research Assistant (MS), Geospatial Information Science &amp; Technology<br>University of Wyoming &mdash; Laramie, WY</p>
    <p class="hes-member-card__bio">Ismail's thesis examines digital-twin readiness in small cities, using Laramie and Afton, Wyoming, as case studies to evaluate whether smaller communities possess the spatial data infrastructure and institutional capacity needed to adopt advanced spatial technologies equitably. Before joining UW, he studied Urban Planning, graduating first in a class of 55. He also brings nearly three years of industry experience as a Software Development Engineer in Test and co-founded NextHunger, a small IT firm. His research interests include GeoAI and Machine Learning, Digital Twins, Transportation Planning, Urban Informatics, Smart and Resilient Communities, and Human&ndash;environment interactions. He plans to pursue doctoral studies in Summer/Fall 2027.</p>
    <div class="hes-member-card__pub">Njoku, J. N., Shukla, D., Katariya, V., Hossain, M. I., &amp; Hawes, J. K. (2026). PANDA: A lightweight digital twin framework for smart parking management. In <em>Proceedings of the ASCE International Conference on Computing in Civil Engineering (i3CE 2026)</em>. Songdo, South Korea.</div>
    <div class="hes-member-card__links">
      <a href="mailto:mhossa14@uwyo.edu">&#9993; mhossa14@uwyo.edu</a>
      <a href="https://www.linkedin.com/in/ismailtimes/" target="_blank">LinkedIn</a>
      <a href="https://ismailtimes.weebly.com/" target="_blank">Website</a>
      <a href="https://github.com/IsmailTimes" target="_blank">GitHub</a>
      <!-- CV: upload /files/hossain_cv.pdf then uncomment:
      <a href="#" class="hes-cv-btn hes-cv-btn--view" data-cv-view="/files/hossain_cv.pdf" data-cv-name="Md. Ismail Hossain">&#128196; View CV</a>
      <a href="/files/hossain_cv.pdf" download class="hes-cv-btn hes-cv-btn--download">&#11015; Download CV</a>
      -->
    </div>
  </div>
</div>

<!-- Sandip Pantha -->
<div class="hes-member-card">
  <img class="hes-member-card__avatar" src="/images/Sandip_Pantha.jpeg" alt="Sandip Pantha">
  <div>
    <div class="hes-member-card__name">Sandip Pantha</div>
    <p class="hes-member-card__title">Graduate Research Assistant (MS), Geographic Information Science &amp; Technology / Environment &amp; Natural Resources<br>University of Wyoming &mdash; Laramie, WY</p>
    <p class="hes-member-card__bio">Sandip is a master's student at the University of Wyoming pursuing a dual major in Geographic Information Science and Technology (GIST) and Environment and Natural Resources (ENRS). His research focuses on the intersection of social vulnerability, climate risk, and geospatial analysis, with a particular interest in wildfire risk, environmental hazards, and community resilience. His current thesis examines the geography of social vulnerability and wildfire risk across Wyoming using spatial analysis and socio-environmental indicators. Before joining UW, he completed a Bachelor of Science in Forestry at Tribhuvan University, Nepal, and worked on several interdisciplinary research projects related to climate change vulnerability, flood-induced migration, and urban water security in Nepal. His technical interests include GIS, remote sensing, Google Earth Engine, R, and spatial data science for environmental decision-making. He is interested in future PhD opportunities related to climate adaptation, socio-environmental systems, geospatial modeling, and applied GIS research.</p>
    <div class="hes-member-card__links">
      <a href="mailto:spantha@uwyo.edu">&#9993; spantha@uwyo.edu</a>
      <a href="https://www.linkedin.com/in/sandip-pantha/" target="_blank">LinkedIn</a>
      <a href="https://orcid.org/0009-0003-2964-2373" target="_blank">ORCID</a>
      <!-- CV: upload /files/pantha_cv.pdf then uncomment:
      <a href="#" class="hes-cv-btn hes-cv-btn--view" data-cv-view="/files/pantha_cv.pdf" data-cv-name="Sandip Pantha">&#128196; View CV</a>
      <a href="/files/pantha_cv.pdf" download class="hes-cv-btn hes-cv-btn--download">&#11015; Download CV</a>
      -->
    </div>
  </div>
</div>


<!-- Nolan Reitz -->
<div class="hes-member-card">
  <img class="hes-member-card__avatar" src="/images/Nolan_Reitz.jpg" alt="Nolan Reitz">
  <div>
    <div class="hes-member-card__name">Nolan Reitz</div>
    <p class="hes-member-card__title">School of Computing Undergraduate Research Experience Fellow &mdash; BS, Computer Engineering, University of Wyoming (Expected May 2028)<br>University of Wyoming &mdash; Laramie, WY</p>
    <p class="hes-member-card__bio">Nolan joined the lab as a School of Computing Undergraduate Research Experience (URE) fellow while working on his BS in Computer Engineering at UW. His fellowship work examined the reproducibility, representativity, and transparency of supervised machine learning models in industrial ecology research &mdash; contributing to a growing conversation about methodological standards at the intersection of ML and sustainability science. His technical interests include the University Rover Challenge, Python, Java, C++, and physical computing. He is interested in future internship opportunities related to robotics, hardware integration, or programming.</p>
    <div class="hes-member-card__pub">Donati, F., Tu, Q., Ward-Bond, J., Reitz, N., Hiser, B., et al. (2026). A call to ensure reproducibility of machine learning applications in industrial ecology. <em>ResearchSquare</em> [preprint]. <a href="https://doi.org/10.21203/rs.3.rs-9270723/v1" target="_blank">https://doi.org/10.21203/rs.3.rs-9270723/v1</a></div>
    <div class="hes-member-card__links">
      <a href="https://www.linkedin.com/in/nolan-reitz-221618383" target="_blank">LinkedIn</a>
    </div>
  </div>
</div>

<hr style="border:none; border-top:1px solid #f0f0f0; margin: 2.5em 0 2em;">

<h2 class="hes-members-heading">Past Lab Members</h2>

<!-- Briana Hiser -->
<div class="hes-member-card">
  <div class="hes-avatar-placeholder" aria-label="Briana Hiser">BH</div>
  <div>
    <div class="hes-member-card__name">Briana Hiser</div>
    <p class="hes-member-card__title">School of Computing Undergraduate Research Experience Fellow &mdash; BS, Architectural Engineering, University of Wyoming (May 2026)</p>
    <p class="hes-member-card__bio">Briana joined the lab as a School of Computing Undergraduate Research Experience (URE) fellow while completing her BS in Architectural Engineering at UW. Her fellowship work examined the reproducibility, representativity, and transparency of supervised machine learning models in industrial ecology research &mdash; contributing to a growing conversation about methodological standards at the intersection of ML and sustainability science.</p>
    <div class="hes-member-card__pub">Donati, F., Tu, Q., Ward-Bond, J., Reitz, N., Hiser, B., et al. (2026). A call to ensure reproducibility of machine learning applications in industrial ecology. <em>ResearchSquare</em> [preprint]. <a href="https://www.researchsquare.com/article/rs-9270723/v1" target="_blank">https://doi.org/10.21203/rs.3.rs-9270723/v1</a></div>
  </div>
</div>

<hr style="border:none; border-top:1px solid #f0f0f0; margin: 2.5em 0 2em;">

<h2 class="hes-members-heading">Join the Lab</h2>

<p>All lab openings will be posted to Jake's LinkedIn. Please feel free to follow him there for regular updates on positions and projects.</p>

<!-- CV modal (shared across all member cards) -->
<div class="hes-cv-modal" id="hes-cv-modal" role="dialog" aria-modal="true" aria-labelledby="hes-cv-modal-title">
  <div class="hes-cv-modal__box">
    <div class="hes-cv-modal__header">
      <span class="hes-cv-modal__title" id="hes-cv-modal-title"></span>
      <div class="hes-cv-modal__actions">
        <a class="hes-cv-modal__download" id="hes-cv-modal-dl" href="#" download>&#11015; Download</a>
        <button class="hes-cv-modal__close" id="hes-cv-modal-close" aria-label="Close CV viewer">&times;</button>
      </div>
    </div>
    <iframe class="hes-cv-modal__iframe" id="hes-cv-modal-iframe" src="" title="CV document"></iframe>
  </div>
</div>

<script>
(function () {
  var modal   = document.getElementById('hes-cv-modal');
  var iframe  = document.getElementById('hes-cv-modal-iframe');
  var titleEl = document.getElementById('hes-cv-modal-title');
  var dlLink  = document.getElementById('hes-cv-modal-dl');
  var closeBtn = document.getElementById('hes-cv-modal-close');

  function openModal(url, name) {
    iframe.src  = url;
    dlLink.href = url;
    titleEl.textContent = name + ' — CV';
    modal.classList.add('is-open');
    document.body.style.overflow = 'hidden';
  }

  function closeModal() {
    modal.classList.remove('is-open');
    iframe.src = '';
    document.body.style.overflow = '';
  }

  document.querySelectorAll('[data-cv-view]').forEach(function (btn) {
    btn.addEventListener('click', function (e) {
      e.preventDefault();
      openModal(this.dataset.cvView, this.dataset.cvName);
    });
  });

  closeBtn.addEventListener('click', closeModal);

  modal.addEventListener('click', function (e) {
    if (e.target === modal) closeModal();
  });

  document.addEventListener('keydown', function (e) {
    if (e.key === 'Escape' && modal.classList.contains('is-open')) closeModal();
  });
}());
</script>
