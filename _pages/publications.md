---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
{% include _config.yml %}
{% if author.googlescholar %}
   You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
   [my Google Scholar profile]({{author.googlescholar}})
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
