---
title:  Overview
---

North Carolina [House Bill 805](https://www.ncleg.gov/BillLookup/2025/H805) is an open attack on transgender and nonbinary people.

{% for post in site.posts %}

---

## [{{ post.title }}]({{ post.url }})

### by {{ post.author | default: site.author }}, {{ post.date | date: "%-d %B %Y" }}

{{ post.content }}

{% endfor %}