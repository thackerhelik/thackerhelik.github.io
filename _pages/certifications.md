---
layout: archive
title: "Certifications"
permalink: /certifications/
author_profile: true
---

{% include base_path %}

Testing certifications page

{% for post in site.certifications %}
  {% include archive-single-certificate.html %}
{% endfor %}