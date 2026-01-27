---
permalink: /
title: #
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% include base_path %}

# Recent Publications
{% for post in site.publications reversed limit:3 %}
  {% include archive-single.html %}
{% endfor %}

# Recent Portfolio Items
{% for post in site.portfolio reversed limit:3 %}
  {% include archive-single.html %}
{% endfor %}

# Recent Blog Posts
{% for post in site.posts reversed limit:3 %}
  {% include archive-single.html %}
{% endfor %}
