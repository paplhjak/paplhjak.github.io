---
layout: splash
permalink: /
title: "Jakub Paplhám — Machine Learning Researcher"
excerpt: "Machine learning researcher at the Czech Technical University in Prague."
redirect_from:
  - /about/
  - /about.html
---

<div class="profile-home">
  <header class="profile-intro">
    <div class="profile-intro__text">
      <h1>Jakub Paplhám</h1>
      <p class="profile-intro__role">Machine Learning Researcher · Czech Technical University in Prague</p>
      <p class="profile-intro__summary">PhD candidate at the Center for Machine Perception. Research interests include uncertainty quantification, reject-option prediction, distribution shift, and computer vision.</p>
      <p class="profile-intro__links"><a href="mailto:paplhjak@fel.cvut.cz">Email</a><a href="https://github.com/paplhjak">GitHub</a><a href="https://orcid.org/0009-0009-7110-293X">ORCID</a></p>
    </div>
    <figure class="profile-photo">
      <img src="{{ base_path }}/images/profile-web.jpg" alt="Jakub Paplhám seated in front of a whiteboard" width="899" height="1125">
      <figcaption>Photo: Petr Neugebauer / FEE CTU</figcaption>
    </figure>
  </header>

  <section class="profile-section" aria-labelledby="research-heading">
    <h2 id="research-heading">Research</h2>
    <ul class="plain-list">
      <li>Uncertainty quantification and reliable prediction</li>
      <li>Reject-option prediction and distribution shift</li>
      <li>Computer vision, facial analysis, and age estimation</li>
    </ul>
  </section>

  <section class="profile-section" aria-labelledby="publications-heading">
    <div class="section-title-row">
      <h2 id="publications-heading">Selected publications</h2>
      <a href="{{ base_path }}/publications/">Full list</a>
    </div>
    <div class="publication-list">
      {% assign featured_publications = site.publications | where: "featured", true | sort: "date" | reverse %}
      {% for post in featured_publications %}{% include publication-card.html post=post %}{% endfor %}
    </div>
  </section>

  <section class="profile-section" aria-labelledby="current-heading">
    <div class="section-title-row">
      <h2 id="current-heading">Experience</h2>
      <a href="{{ base_path }}/cv/">CV</a>
    </div>
    <div class="compact-entries">
      <div class="compact-entry"><span>2022–present</span><p><strong>Researcher and PhD candidate</strong><br>Center for Machine Perception, CTU Prague</p></div>
      <div class="compact-entry"><span>2026</span><p><strong>Visiting researcher</strong><br>LMU Munich</p></div>
      <div class="compact-entry"><span>2021–2024</span><p><strong>Machine learning engineer</strong><br>Porsche Engineering via CIIRC CTU</p></div>
    </div>
  </section>

  <section class="profile-section" aria-labelledby="recognition-heading">
    <h2 id="recognition-heading">Recognition</h2>
    <div class="compact-entries">
      <div class="compact-entry"><span>2026</span><p><strong>Dean's Award for Outstanding Teaching</strong><br>Only teaching assistant honoured at FEE CTU, winter 2025/26</p></div>
      <div class="compact-entry"><span>2025</span><p><strong>Minister of the Interior Award</strong><br>FACIS project</p></div>
      <div class="compact-entry"><span>2022</span><p><strong>Dean's Award</strong><br>Master's thesis</p></div>
    </div>
  </section>

  <section class="profile-section" id="contact" aria-labelledby="contact-heading">
    <h2 id="contact-heading">Contact</h2>
    <p class="contact-lines"><a href="mailto:paplhjak@fel.cvut.cz">paplhjak@fel.cvut.cz</a><br>Center for Machine Perception, Karlovo náměstí 13, Prague</p>
  </section>
</div>
