---
layout: page
title:  "Publications"
permalink:  "publications"
categories: poetry books chapbooks
---

h2. Chapbooks

{% for chapbook in site.data.poetry.chapbooks %}
- {{chapbook.title}}
{% endfor %}