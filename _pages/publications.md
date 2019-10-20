---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<i>PDF copies and links to OSF and GitHub repos for data and task scripts can be found in each individual page.</i> 

  <ol reversed>{% for post in site.publications reversed%}
    {% include archive-single-cv.html %}
  {% endfor %}</ol>

