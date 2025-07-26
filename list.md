---
title:  Overview
---

North Carolina [House Bill 805](https://www.ncleg.gov/BillLookup/2025/H805) is an open attack on transgender and nonbinary people.

{% for post in site.posts %}

---

<small>{{ post.date | date: "%-d %B %Y" }}</small>
<h2><a href="{{ post.url}}">{{ post.title }}</a></h2>
<p class="view">by {{ post.author | default: site.author }}</p>

{{ post.content }}

{% endfor %}