---
layout: splash
permalink: /
title: "Hawes Social-Environmental Systems Research Group"
redirect_from:
  - /about/
  - /about.html
---

<style>
/* ── Hero ──────────────────────────────────────────────── */
.hes-hero {
  position: relative;
  left: 50%;
  right: 50%;
  margin-left: -50vw;
  margin-right: -50vw;
  width: 100vw;
  min-height: 520px;
  background: #0c1f16;
  display: flex;
  align-items: center;
  justify-content: center;
  overflow: hidden;
  margin-bottom: 3.5em;
}
@media (max-width: 768px) {
  .hes-hero { min-height: 380px; }
}
.hes-hero__bg {
  position: absolute; inset: 0;
  width: 100%; height: 100%;
  object-fit: cover; opacity: 0.28;
}
.hes-hero__body {
  position: relative;
  text-align: center;
  padding: 4em 2em;
  max-width: 780px;
}
.hes-hero__label {
  font-size: 0.68rem; font-weight: 700;
  color: #6dd9a8; letter-spacing: 0.16em;
  text-transform: uppercase; margin-bottom: 1.3em;
}
.hes-hero__title {
  font-size: clamp(2.2rem, 5vw, 3.8rem);
  font-weight: 800; color: #fff;
  line-height: 1.1; letter-spacing: -0.03em;
  margin: 0 0 0.8em;
}
.hes-hero__sub {
  font-size: 0.95rem; color: rgba(255,255,255,0.55);
  letter-spacing: 0.06em; margin: 0 0 2.2em;
}
.hes-hero__ctas { display: flex; gap: 0.9em; justify-content: center; flex-wrap: wrap; }
.hes-btn-primary {
  background: #6dd9a8; color: #0c1f16;
  padding: 0.72em 1.7em; border-radius: 4px;
  text-decoration: none; font-weight: 700; font-size: 0.83rem;
  letter-spacing: 0.02em;
}
.hes-btn-primary:hover { background: #55c994; color: #0c1f16; text-decoration: none; }
.hes-btn-secondary {
  background: transparent; color: #fff;
  padding: 0.72em 1.7em; border-radius: 4px;
  text-decoration: none; font-weight: 600; font-size: 0.83rem;
  border: 1px solid rgba(255,255,255,0.35);
}
.hes-btn-secondary:hover { border-color: rgba(255,255,255,0.7); color: #fff; text-decoration: none; }

/* ── Research area cards ───────────────────────────────── */
.hes-research-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 1.2em; margin-bottom: 3.5em;
}
@media (max-width: 640px) { .hes-research-grid { grid-template-columns: 1fr; } }
.hes-research-card {
  padding: 1.5em 1.4em;
  border: 1px solid #e5e5e5; border-radius: 6px; background: #fff;
}
.hes-research-card__tag {
  font-size: 0.64rem; font-weight: 700;
  letter-spacing: 0.12em; text-transform: uppercase;
  color: #2a6e49; margin-bottom: 0.55em;
}
.hes-research-card__title {
  font-size: 0.95rem; font-weight: 700;
  color: #111; margin-bottom: 0.45em;
}
.hes-research-card__desc { font-size: 0.84rem; color: #555; line-height: 1.6; }

/* ── Body sections ─────────────────────────────────────── */
.hes-section { margin-bottom: 3em; }
.hes-section h2 {
  font-size: 1.3rem; font-weight: 700;
  letter-spacing: -0.02em;
  border-bottom: 2px solid #f0f0f0;
  padding-bottom: 0.45em; margin-bottom: 1em; margin-top: 0;
}
.hes-section p { font-size: 0.92rem; line-height: 1.8; color: #333; margin-bottom: 0.9em; }

/* ── News list ─────────────────────────────────────────── */
.hes-news { list-style: none; padding: 0; margin: 0; }
.hes-news li {
  padding: 0.9em 0; border-bottom: 1px solid #f0f0f0;
  font-size: 0.88rem; color: #333; line-height: 1.55;
}
.hes-news li:last-child { border-bottom: none; }

/* ── Explore grid ──────────────────────────────────────── */
.hes-explore {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 0.8em; margin-top: 0.5em;
}
@media (max-width: 640px) { .hes-explore { grid-template-columns: 1fr; } }
.hes-explore-card {
  display: block; padding: 1.1em 1.3em;
  border: 1px solid #e5e5e5; border-radius: 6px;
  text-decoration: none; color: #111;
}
.hes-explore-card:hover {
  border-color: #2a6e49; background: #f6fbf8;
  color: #2a6e49; text-decoration: none;
}
.hes-explore-card__title { font-weight: 700; font-size: 0.88rem; }
.hes-explore-card__desc { font-size: 0.78rem; color: #777; margin-top: 0.2em; }
</style>

<!-- Hero -->
<div class="hes-hero">
  <img class="hes-hero__bg" src="/images/Sutton_clipped.jpg" alt="">
  <div class="hes-hero__body">
    <div class="hes-hero__label">Hawes Research Group &middot; University of Wyoming</div>
    <h1 class="hes-hero__title">Human-Environmental<br>Systems Lab</h1>
    <p class="hes-hero__sub">Sustainability &nbsp;&middot;&nbsp; Resilience &nbsp;&middot;&nbsp; Justice</p>
    <div class="hes-hero__ctas">
      <a href="/projects/" class="hes-btn-primary">Our Projects</a>
      <a href="/lab-members/" class="hes-btn-secondary">Meet the Team</a>
    </div>
  </div>
</div>

<!-- Research areas -->
<div class="hes-research-grid">
  <div class="hes-research-card">
    <div class="hes-research-card__tag">Research Area</div>
    <div class="hes-research-card__title">Urban Agriculture</div>
    <div class="hes-research-card__desc">Food-energy-water nexus in cities and community green spaces</div>
  </div>
  <div class="hes-research-card">
    <div class="hes-research-card__tag">Research Area</div>
    <div class="hes-research-card__title">Infrastructure Resilience</div>
    <div class="hes-research-card__desc">Modeling critical systems under environmental and social stress</div>
  </div>
  <div class="hes-research-card">
    <div class="hes-research-card__tag">Research Area</div>
    <div class="hes-research-card__title">Natural Hazards</div>
    <div class="hes-research-card__desc">Community adaptive capacity and social vulnerability to hazards</div>
  </div>
</div>

<!-- About -->
<div class="hes-section">
<h2>Welcome to the Hawes Lab</h2>
<p>The Hawes Social-Environmental Systems Research Group studies <strong>sustainability, resilience, and justice</strong> in coupled natural-human systems. We are based at the <a href="https://www.uwyo.edu">University of Wyoming</a>, where Jake Hawes is jointly appointed in the <a href="https://www.uwyo.edu/cosc/">School of Computing</a> and the <a href="https://www.uwyo.edu/haub/">Haub School of Environment and Natural Resources</a>.</p>
<p>Our work draws on planning, geography, and engineering to understand how built, natural, and social systems interact — and how thoughtful design and policy can promote more equitable and resilient outcomes.</p>
</div>

<hr style="border:none; border-top:1px solid #f0f0f0; margin:0 0 3em;">

<!-- About Jake -->
<div class="hes-section">
<h2>About Jake</h2>
<p>Jake Hawes is an Assistant Professor co-appointed between the School of Computing and the Haub School of Environment and Natural Resources at the University of Wyoming. His research deploys mixed methods and interdisciplinary analysis to model coupled natural-human systems across scales — from individual farmers to regional food-energy-water systems.</p>
<p>Jake earned his PhD from the University of Michigan School for Environment and Sustainability, and holds a BS in Environmental and Ecological Engineering and an MS in Natural Resources Social Science from Purdue University. His work has been supported by NSF, USDA, and Sea Grant, and has appeared in journals including <em>Nature Cities</em>, <em>Landscape and Urban Planning</em>, and <em>Environmental Science &amp; Technology</em>.</p>
<p>Reach Jake at <a href="mailto:jhawes@uwyo.edu">jhawes@uwyo.edu</a></p>
</div>

<hr style="border:none; border-top:1px solid #f0f0f0; margin:0 0 3em;">

<!-- News -->
<div class="hes-section">
<h2>News &amp; Updates</h2>
<ul class="hes-news">
  <li><strong>Spring 2025</strong> — New paper published in <em>Nature Cities</em>: <a href="https://www.nature.com/articles/s44284-023-00023-3">Comparing the carbon footprints of urban and conventional agriculture</a></li>
  <li><strong>Fall 2025</strong> — Jake begins teaching new courses at the intersection of computing and coupled natural-human systems at UW</li>
  <li><strong>Now recruiting</strong> — The lab is actively seeking a postdoc. Send your CV and a brief statement of interests (&le;2 pages) to <a href="mailto:jhawes@uwyo.edu">jhawes@uwyo.edu</a></li>
</ul>
</div>

<hr style="border:none; border-top:1px solid #f0f0f0; margin:0 0 3em;">

<!-- Explore -->
<div class="hes-section">
<h2>Explore the Site</h2>
<div class="hes-explore">
  <a href="/lab-members/" class="hes-explore-card">
    <div class="hes-explore-card__title">Lab Members</div>
    <div class="hes-explore-card__desc">Meet the team</div>
  </a>
  <a href="/projects/" class="hes-explore-card">
    <div class="hes-explore-card__title">Projects</div>
    <div class="hes-explore-card__desc">Current and past research</div>
  </a>
  <a href="/publications/" class="hes-explore-card">
    <div class="hes-explore-card__title">Publications</div>
    <div class="hes-explore-card__desc">Journal articles and papers</div>
  </a>
  <a href="/talks/" class="hes-explore-card">
    <div class="hes-explore-card__title">Talks</div>
    <div class="hes-explore-card__desc">Presentations and invited lectures</div>
  </a>
  <a href="/teaching/" class="hes-explore-card">
    <div class="hes-explore-card__title">Teaching</div>
    <div class="hes-explore-card__desc">Courses at UW</div>
  </a>
</div>
</div>
