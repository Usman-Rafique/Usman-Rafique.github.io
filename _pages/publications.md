---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---
Please see the full list of my publications on my [Google Scholar profile](http://scholar.google.com/citations?user=Q84PBTQAAAAJ&hl=en).

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
