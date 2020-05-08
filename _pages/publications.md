---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

You can find my complete list of my scientific publications on [Orcid](https://orcid.org/0000-0002-0650-9903).
  

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
