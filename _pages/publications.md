---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


You can also find my full publication list on <a href="https://scholar.google.com/citations?user=PBLq5PoAAAAJ&hl=en&authuser=1">my Google Scholar profile</a>.


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
