---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

<p style="margin-bottom: 1.5em;">
  <a href="https://scholar.google.com/citations?hl=en&user=Rbvo1wYAAAAJ" target="_blank" style="margin-right: 1em;"><i class="ai ai-google-scholar ai-fw"></i> Google Scholar</a>
  <a href="https://www.researchgate.net/profile/Lin-Legeng" target="_blank"><i class="ai ai-researchgate ai-fw"></i> ResearchGate</a>
</p>

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
