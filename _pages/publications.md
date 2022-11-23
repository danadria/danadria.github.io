---
layout: archive
title: "Publications"
excerpt: "Daniel Anadria Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on [my Google Scholar page](https://scholar.google.com/citations?hl=en&user=E5wiCxMAAAAJ).

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
