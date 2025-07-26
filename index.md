---
title:  Overview
---

North Carolina [House Bill 805](https://www.ncleg.gov/BillLookup/2025/H805) is an open attack on transgender and nonbinary people.

For more information, please see:

* [A summary of HB-805 from the ACLU of North Carolina](https://www.acluofnorthcarolina.org/en/legislation/hb-805-anti-transschool-censorship-bill)
* [Information about Gender-Affirming Healthcare from the Human Rights Campaign](https://www.hrc.org/resources/get-the-facts-on-gender-affirming-care)

The following essays are from local North Carolina residents.

{% for post in site.tags.pinned %}

---

## [{{ post.title }}]({{ post.url }})

### by {{ post.author | default: site.author }}, {{ post.date | date: "%-d %B %Y" }}

{{ post.content }}

{% endfor %}

{% for post in site.posts %}
{% if 'pinned' in post.tags or 'wip' in post.tags %}
{% continue %}
{% endif %}

---

## [{{ post.title }}]({{ post.url }})

### by {{ post.author | default: site.author }}, {{ post.date | date: "%-d %B %Y" }}

{{ post.content }}

{% endfor %}