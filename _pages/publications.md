---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">View my publications on <a href="{{https://ui.adsabs.harvard.edu/public-libraries/sHUu1MclQgaV6oRt2fx_PQ}}">NASA/ADS</a> or <a href="{{https://arxiv.org/search/?searchtype=author&query=Gakis%2C+D}}">arXiv</a>. or link [NASA/ADS](https://ui.adsabs.harvard.edu/public-libraries/sHUu1MclQgaV6oRt2fx_PQ)  </div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
