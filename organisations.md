---
title: Organisations List
permalink: /organisations/
---

{{page.path}}

# List of All Organisations
{% for org in site.data.organisations limit:50 %}
* [{{ org.name }}]({{ org.name | datapage_url: "organisations" | relative_url }})
{% endfor %}
