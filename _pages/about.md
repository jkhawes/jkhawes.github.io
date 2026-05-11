---
layout: splash
permalink: /
title: "Hawes Social-Environmental Systems Research Group"
redirect_from:
  - /about/
  - /about.html
---

<style>
/* ── Home-page: transparent nav over hero ──────────────── */
.masthead {
  position: absolute !important;
  top: 0; left: 0; right: 0;
  background: transparent !important;
  border-bottom: none !important;
  box-shadow: none !important;
}
.greedy-nav { background: transparent !important; }
.greedy-nav a { color: rgba(255,255,255,0.88) !important; }
.greedy-nav a:hover { color: #6dd9a8 !important; }
.greedy-nav .visible-links a::before { background: #6dd9a8 !important; }
.masthead__submenu {
  background: rgba(12,31,22,0.96) !important;
  border-color: rgba(255,255,255,0.12) !important;
}
.masthead__submenu li a { color: rgba(255,255,255,0.82) !important; }
.masthead__submenu li a:hover {
  background: rgba(255,255,255,0.08) !important;
  color: #6dd9a8 !important;
}

/* ── Kill the body padding-top set by masthead JS + #main margin ── */
body { padding-top: 0 !important; }
#main { margin-top: 0 !important; }

/* ── Unclip parent containers so full-bleed can escape ─── */
#main, #main > article, #main .page__content {
  overflow: visible !important;
}

/* ── Hero ──────────────────────────────────────────────── */
.hes-hero {
  position: relative;
  left: 50%;
  transform: translateX(-50%);
  width: 100vw;
  height: 100vh;
  background: #0c1f16;
  display: flex;
  align-items: center;
  justify-content: center;
  overflow: hidden;
  margin-bottom: 3.5em;
}
@media (max-width: 768px) {
  .hes-hero { height: 80vh; }
}
.hes-hero__bg {
  position: absolute; inset: 0;
  width: 100%; height: 100%;
  object-fit: cover; opacity: 0.28;
}
.hes-hero__body {
  position: relative;
  text-align: center;
  padding: 7em 2em 4em;
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
a.hes-research-card {
  display: block;
  padding: 1.5em 1.4em;
  border: 1px solid #e5e5e5; border-radius: 6px; background: #fff;
  text-decoration: none; color: inherit;
}
a.hes-research-card:hover {
  border-color: #2a6e49; background: #f6fbf8; text-decoration: none;
}
a.hes-research-card:hover .hes-research-card__title { color: #2a6e49; }
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
  <img class="hes-hero__bg" src="/images/WinterTeton.jpg" alt="">
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

<!-- About -->
<div class="hes-section">
<h2>Welcome to the Hawes Lab</h2>
<p>The Hawes Social-Environmental Systems Research Group studies <strong>sustainability, resilience, and justice</strong> in coupled natural-human systems. We are based at the <a href="https://www.uwyo.edu">University of Wyoming</a>, where Jake Hawes is jointly appointed in the <a href="https://www.uwyo.edu/cosc/">School of Computing</a> and the <a href="https://www.uwyo.edu/haub/">Haub School of Environment and Natural Resources</a>.</p>
<p>Our work draws on planning, geography, and engineering to understand how built, natural, and social systems interact &mdash; and how thoughtful design and policy can promote more equitable and resilient outcomes. <a href="/lab-members/">Meet the team &rarr;</a></p>
</div>

<!-- Research area cards -->
<div class="hes-research-grid">
  <a href="/projects/smart-rural-places/" class="hes-research-card">
    <div class="hes-research-card__tag">Smart Communities</div>
    <div class="hes-research-card__title">Smart Rural Places</div>
    <div class="hes-research-card__desc">Exploring the role of smart systems and AI in rural places and small towns</div>
  </a>
  <a href="/projects/infrastructure-resilience/" class="hes-research-card">
    <div class="hes-research-card__tag">Resilience</div>
    <div class="hes-research-card__title">Infrastructure Resilience</div>
    <div class="hes-research-card__desc">Resilient and sustainable infrastructure in rural and remote areas</div>
  </a>
  <a href="/projects/climes/" class="hes-research-card">
    <div class="hes-research-card__tag">Hazards &amp; Modeling</div>
    <div class="hes-research-card__title">CLIMES</div>
    <div class="hes-research-card__desc">Collaborative modeling of hazard impacts on social-ecological-economic systems</div>
  </a>
  <a href="/projects/circular-economy/" class="hes-research-card">
    <div class="hes-research-card__tag">Sustainability</div>
    <div class="hes-research-card__title">Circular Economy</div>
    <div class="hes-research-card__desc">Research on circular economy principles and their application to sustainable systems</div>
  </a>
  <a href="/projects/food-systems/" class="hes-research-card">
    <div class="hes-research-card__tag">Food Security</div>
    <div class="hes-research-card__title">Food Systems</div>
    <div class="hes-research-card__desc">Research on sustainable and resilient food systems</div>
  </a>
</div>

<hr style="border:none; border-top:1px solid #f0f0f0; margin:0 0 3em;">

<!-- News -->
<div class="hes-section">
<h2>News &amp; Updates</h2>
{% assign recent_posts = site.posts | limit: 3 %}
{% if recent_posts.size > 0 %}
<ul class="hes-news">
  {% for post in recent_posts %}
  <li>
    <strong>{{ post.date | date: "%B %Y" }}</strong> &mdash;
    <a href="{{ post.url }}">{{ post.title }}</a>
    {% if post.excerpt %}<br><span style="color:#777; font-size:0.85em;">{{ post.excerpt | strip_html | truncate: 140 }}</span>{% endif %}
  </li>
  {% endfor %}
</ul>
{% else %}
<p style="color:#888; font-style:italic; font-size:0.9rem;">No posts yet.</p>
{% endif %}
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
