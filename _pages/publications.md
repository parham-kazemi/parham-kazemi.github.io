---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
  You can also find my articles on <u><a href="{{[https://scholar.google.com/citations?view_op=view_citation&hl=en&user=uaPbSnIAAAAJ&citation_for_view=uaPbSnIAAAAJ:u5HHmVD_uO8C]}}">my Google Scholar profile</a>.</u>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
