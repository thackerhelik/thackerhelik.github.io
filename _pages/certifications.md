---
layout: archive
title: "Certifications"
permalink: /certifications/
author_profile: true
---

{% include base_path %}

Testing certifications page

{% for post in site.certifications reversed %}
  TestL
  {% include archive-single-certificate.html %}
{% endfor %}

{% for post in site.publications reversed %}
  TestM
  {% include archive-single-certificate.html %}
{% endfor %}
