---
layout: default
title: Authors
permalink: /authors/
sitemap:
  priority: 0.7
---

{% for author in site.authors %}
* <img src="/images/profile/{{author.github}}.jpg" width="25px"> [{{ author.title }}]({{ site.baseurl }}/authors/{{ author.github }}/)
{% endfor %}
