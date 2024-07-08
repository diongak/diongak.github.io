---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

  <div class="wordwrap">View my publications on <a href="{{https://ui.adsabs.harvard.edu/public-libraries/sHUu1MclQgaV6oRt2fx_PQ}}">NASA/ADS</a> or <a href="{{https://arxiv.org/search/?searchtype=author&query=Gakis%2C+D}}">arXiv</a>. </div>
  
  View my publications on [NASA/ADS](https://ui.adsabs.harvard.edu/public-libraries/sHUu1MclQgaV6oRt2fx_PQ) or 
[arXiv](https://arxiv.org/search/?searchtype=author&query=Gakis%2C+D).
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
