---
layout: splash
permalink: /
title: "Jakub Paplhám — Machine Learning Researcher"
excerpt: "Machine learning researcher working on reliable prediction, uncertainty, distribution shift, and computer vision."
redirect_from:
  - /about/
  - /about.html
---

<div class="research-home">
  <section class="research-home__hero" aria-labelledby="intro-title">
    <div>
      <p class="eyebrow">Machine Learning Researcher · Prague</p>
      <h1 class="research-home__title" id="intro-title">Jakub<br>Paplhám</h1>
      <p class="research-home__lead">I study how machine-learning systems can know when they do not know—building reliable predictors for uncertain, shifting, and real-world data.</p>
      <div class="hero-actions">
        <a class="jp-button" href="{{ base_path }}/publications/">Explore publications</a>
        <a class="jp-button jp-button--ghost" href="https://github.com/paplhjak">View GitHub</a>
      </div>
    </div>
    <figure class="hero-portrait">
      <img src="{{ base_path }}/images/profile-web.jpg" alt="Jakub Paplhám seated in front of a whiteboard" width="899" height="1125">
      <figcaption class="hero-portrait__note">PhD Candidate · CTU</figcaption>
      <span class="hero-portrait__credit">Photo: Petr Neugebauer / FEE CTU</span>
    </figure>
  </section>

  <div class="proof-strip" aria-label="Research highlights">
    <div class="proof-strip__item"><strong>CVPR · ECCV · WACV</strong><span>Peer-reviewed computer vision research</span></div>
    <div class="proof-strip__item"><strong>CTU Prague</strong><span>Center for Machine Perception</span></div>
    <div class="proof-strip__item"><strong>Open research</strong><span>Benchmarks, datasets, and software</span></div>
    <div class="proof-strip__item"><strong>Theory → practice</strong><span>Reliable ML for consequential systems</span></div>
  </div>

  <section class="jp-section" id="research" aria-labelledby="research-heading">
    <div class="section-heading">
      <div>
        <p class="eyebrow">Research</p>
        <h2 id="research-heading">Making predictions more trustworthy.</h2>
      </div>
      <p>My work spans general machine learning and computer vision. I am particularly interested in the boundary between what a model has learned and where it should abstain, adapt, or ask for more information.</p>
    </div>
    <div class="research-grid">
      <article class="research-card">
        <span class="research-card__number">01</span>
        <h3>Uncertainty & reliable ML</h3>
        <p>Principled ways to distinguish uncertainty in the data from uncertainty caused by limited knowledge—and to turn that distinction into better decisions.</p>
      </article>
      <article class="research-card">
        <span class="research-card__number">02</span>
        <h3>Distribution shift & rejection</h3>
        <p>Predictors that recognize unfamiliar inputs, quantify the cost of being wrong, and abstain when the available evidence is insufficient.</p>
      </article>
      <article class="research-card">
        <span class="research-card__number">03</span>
        <h3>Computer vision & evaluation</h3>
        <p>Facial analysis, age estimation, large-scale datasets, and reproducible benchmarks that expose what actually drives model performance.</p>
      </article>
    </div>
  </section>

  <section class="jp-section" aria-labelledby="selected-work-heading">
    <div class="section-heading">
      <div>
        <p class="eyebrow">Selected work</p>
        <h2 id="selected-work-heading">Recent publications.</h2>
      </div>
      <p>Research across personalized prediction, facial analysis, selective classification, and uncertainty. The full list includes peer-reviewed work, public preprints, and theses.</p>
    </div>
    <div class="publication-grid">
      {% assign featured_publications = site.publications | where: "featured", true | sort: "date" | reverse %}
      {% for post in featured_publications limit:3 %}
        {% include publication-card.html post=post %}
      {% endfor %}
    </div>
    <div class="hero-actions">
      <a class="jp-button jp-button--ghost" href="{{ base_path }}/publications/">See all publications</a>
    </div>
  </section>

  <section class="jp-section" aria-labelledby="open-source-heading">
    <div class="section-heading">
      <div>
        <p class="eyebrow">Open source</p>
        <h2 id="open-source-heading">Research you can use.</h2>
      </div>
      <p>I publish implementations and infrastructure alongside research, from reproducible evaluation tooling to efficient point-cloud transport for ROS.</p>
    </div>
    <div class="project-grid">
      <article class="project-card">
        <span class="project-card__language">Python · Benchmark</span>
        <h3>Facial Age Estimation Benchmark</h3>
        <p>A unified, reproducible evaluation suite comparing deep-learning approaches for facial age estimation.</p>
        <a href="https://github.com/paplhjak/Facial-Age-Estimation-Benchmark">Explore repository →</a>
      </article>
      <article class="project-card">
        <span class="project-card__language">C++ · ROS</span>
        <h3>point_cloud_transport</h3>
        <p>An official ROS package that abstracts compressed and alternative over-the-wire representations for point clouds.</p>
        <a href="https://github.com/paplhjak/point_cloud_transport">Explore repository →</a>
      </article>
      <article class="project-card">
        <span class="project-card__language">C++ · Compression</span>
        <h3>Draco transport plugin</h3>
        <p>A Google Draco-based transport plugin for streaming PointCloud2 messages over constrained connections.</p>
        <a href="https://github.com/paplhjak/draco_point_cloud_transport">Explore repository →</a>
      </article>
    </div>
  </section>

  <section class="jp-section" aria-labelledby="experience-heading">
    <div class="section-heading">
      <div>
        <p class="eyebrow">Experience</p>
        <h2 id="experience-heading">Across theory, teaching, and deployed ML.</h2>
      </div>
      <p>My work combines theoretical questions with practical systems: academic research at CTU and LMU, graduate teaching, and perception engineering for autonomous driving.</p>
    </div>
    <div class="timeline">
      <article class="timeline__item"><div class="timeline__date">2022 — present</div><div class="timeline__body"><h3>Researcher & PhD Candidate · CTU Prague</h3><p>Research in reliable machine learning and computer vision at the Center for Machine Perception. Contributor to the award-winning FACIS security-research project and CTU's NIST face-analysis evaluation.</p></div></article>
      <article class="timeline__item"><div class="timeline__date">2026</div><div class="timeline__body"><h3>Visiting Researcher · LMU Munich</h3><p>Research stay with Prof. Eyke Hüllermeier's group focused on uncertainty quantification in machine learning.</p></div></article>
      <article class="timeline__item"><div class="timeline__date">2023 — present</div><div class="timeline__body"><h3>Teaching Assistant · Statistical Machine Learning</h3><p>Leading theoretical and practical graduate seminars and supervising Bachelor's and Master's theses.</p></div></article>
      <article class="timeline__item"><div class="timeline__date">2021 — 2024</div><div class="timeline__body"><h3>Machine Learning Engineer · Porsche Engineering</h3><p>Developed perception algorithms for adaptive cruise control, radar-based road geometry, and camera-based road-surface analysis.</p></div></article>
    </div>
    <div class="hero-actions"><a class="jp-button jp-button--ghost" href="{{ base_path }}/cv/">Full experience & education</a></div>
  </section>

  <section class="jp-section" aria-labelledby="recognition-heading">
    <div class="section-heading">
      <div><p class="eyebrow">Recognition</p><h2 id="recognition-heading">Selected awards.</h2></div>
      <p>Recognition for research with real-world impact, teaching, academic work, and technical problem solving.</p>
    </div>
    <div class="award-grid">
      <article class="award-card"><h3>Minister of the Interior Award</h3><p>FACIS project · Outstanding security research, 2025</p></article>
      <article class="award-card"><h3>Teaching excellence</h3><p>CTU recognition for outstanding graduate instruction</p></article>
      <article class="award-card"><h3>Dean's Award</h3><p>Master's thesis · CTU Faculty of Electrical Engineering</p></article>
    </div>
  </section>

  <section class="jp-section" id="contact" aria-labelledby="contact-heading">
    <div class="contact-panel">
      <div>
        <p class="eyebrow">Contact</p>
        <h2 id="contact-heading">Let’s discuss research.</h2>
        <p>For collaboration, research questions, teaching, or applied machine-learning work, email is the best place to start.</p>
        <div class="contact-links">
          <a class="jp-button" href="mailto:paplhjak@fel.cvut.cz">Email Jakub</a>
          <a class="jp-button jp-button--ghost" href="https://orcid.org/0009-0009-7110-293X">ORCID</a>
        </div>
      </div>
      <ul class="contact-list">
        <li><strong>Academic</strong> <a href="mailto:paplhjak@fel.cvut.cz">paplhjak@fel.cvut.cz</a></li>
        <li><strong>Personal</strong> <a href="mailto:paplham.jakub@gmail.com">paplham.jakub@gmail.com</a></li>
        <li><strong>Office</strong> Building G, Room 105</li>
        <li><strong>Address</strong> Karlovo náměstí 13, 121 35 Prague 2</li>
        <li><strong>Office phone</strong> <a href="tel:+420224355729">+420 224 355 729</a></li>
        <li><strong>Personal phone</strong> <a href="tel:+420775417522">+420 775 417 522</a></li>
      </ul>
    </div>
  </section>
</div>
