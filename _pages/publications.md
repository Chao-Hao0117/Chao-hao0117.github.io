---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

## 硕士毕业论文 (Master Thesis)

{% for post in site.publications reversed %}
  {% if post.type == 'Thesis' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

---

## 期刊发表 (Journal Papers)

{% for post in site.publications reversed %}
  {% if post.type == 'Paper' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
