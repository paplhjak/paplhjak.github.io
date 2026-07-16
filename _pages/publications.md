---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: false
excerpt: "Peer-reviewed papers, public preprints, and theses by Jakub Paplhám."
---

<p class="page-intro">My research covers reliable machine learning, uncertainty, prediction under distribution shift, and computer vision. Published work is linked to the official proceedings whenever available.</p>

{% assign peer_reviewed = site.publications | where: "kind", "peer-reviewed" | sort: "date" | reverse %}
{% assign preprints = site.publications | where: "kind", "preprint" | sort: "date" | reverse %}
{% assign theses = site.publications | where: "kind", "thesis" | sort: "date" | reverse %}

<p class="publication-list__year">Peer-reviewed</p>
<div class="publication-list">
{% for post in peer_reviewed %}{% include publication-card.html post=post %}{% endfor %}
</div>

<p class="publication-list__year">Public preprints</p>
<div class="publication-list">
{% for post in preprints %}{% include publication-card.html post=post %}{% endfor %}
</div>

<p class="publication-list__year">Theses</p>
<div class="publication-list">
{% for post in theses %}{% include publication-card.html post=post %}{% endfor %}
</div>
