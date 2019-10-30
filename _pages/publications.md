---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You may also find my publications on <u><a href="https://scholar.google.com/citations?user=GclpZkkAAAAJ&hl=en">my Google Scholar profile</a>.</u>

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
