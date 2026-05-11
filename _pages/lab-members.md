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
    </div>
  </div>
</div>

<h2 class="hes-members-heading">Current Lab Members</h2>

<!-- ═══════════════════════════════════════════════════════════
     ADD MEMBER CARDS BELOW — copy the block and fill in fields
     ═══════════════════════════════════════════════════════════ -->

<p style="color:#888; font-size:0.9rem; font-style:italic;">Member profiles coming soon.</p>

<hr style="border:none; border-top:1px solid #f0f0f0; margin: 2.5em 0 2em;">

<h2 class="hes-members-heading">Join the Lab</h2>

<p>The lab is actively recruiting a postdoctoral researcher. Interested candidates should send a CV and brief statement of interests (no more than two pages) to Jake at <a href="mailto:jhawes@uwyo.edu">jhawes@uwyo.edu</a>.</p>
