---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: false
excerpt: "Publications by Jakub Paplhám."
---

{% assign peer_reviewed = site.publications | where: "kind", "peer-reviewed" | sort: "date" | reverse %}
{% assign preprints = site.publications | where: "kind", "preprint" | sort: "date" | reverse %}
{% assign theses = site.publications | where: "kind", "thesis" | sort: "date" | reverse %}

<section class="publication-group" aria-labelledby="reviewed-heading">
  <h2 id="reviewed-heading">Peer-reviewed</h2>
  <div class="publication-list">{% for post in peer_reviewed %}{% include publication-card.html post=post %}{% endfor %}</div>
</section>

<section class="publication-group" aria-labelledby="preprints-heading">
  <h2 id="preprints-heading">Preprints</h2>
  <div class="publication-list">{% for post in preprints %}{% include publication-card.html post=post %}{% endfor %}</div>
</section>

<section class="publication-group" aria-labelledby="theses-heading">
  <h2 id="theses-heading">Theses</h2>
  <div class="publication-list">{% for post in theses %}{% include publication-card.html post=post %}{% endfor %}</div>
</section>
