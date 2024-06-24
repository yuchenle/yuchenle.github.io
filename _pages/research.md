---
title: ""
permalink: /research/
author_profile: true
---
<!-- SEE https://getbootstrap.com/docs/4.4/components/buttons/ FOR INTERESTING WIDGETS! -->

{% if site.author.googlescholar %}
  You can also find my articles on <u><a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

Publications
---------
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Contributions to Other Projects:
-------
[LLVM implementation](https://reviews.llvm.org/D146642) of record & replay of OpenMP tasks.