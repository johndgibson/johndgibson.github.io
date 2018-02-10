---
layout: page
title:  "Publications"
permalink:  "publications"
categories: poetry books chapbooks
---

## Chapbooks

{% for chapbook in site.data.poetry.chapbooks %}
- [{{chapbook.title}}](/{{chapbook.slug}})
{% endfor %}