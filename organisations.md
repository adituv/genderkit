---
title: Organisations List
permalink: /organisations/
---

{{page.path}}

# List of All Organisations
{% for org in site.data.organisations limit:20%}
* [{{ org.name }}]({{org.name | datapage_url: people}}) - {{ org.url }}
{% endfor %}