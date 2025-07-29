---
title:  Overview
---

North Carolina [House Bill 805](https://www.ncleg.gov/BillLookup/2025/H805) is an open attack on transgender and nonbinary people.

For more information, please see:

* [A summary of HB-805 from the ACLU of North Carolina](https://www.acluofnorthcarolina.org/en/legislation/hb-805-anti-transschool-censorship-bill)
* [Information about Gender-Affirming Healthcare from the Human Rights Campaign](https://www.hrc.org/resources/get-the-facts-on-gender-affirming-care)

The following essays are from local North Carolina residents.

{% for post in site.tags.pinned %}
{% unless post.tags contains 'wip' %}

---

## [{{ post.title }}]({{ post.url }})

### by {{ post.author | default: site.author }} on {{ post.date | date: "%B %-d %Y" }}

{{ post.content }}

{% endunless %}
{% endfor %}

{% for post in site.posts %}
{% unless post.tags contains 'pinned' %}
{% unless post.tags contains 'wip' %}

---

## [{{ post.title }}]({{ post.url }})

### by {{ post.author | default: site.author }} on {{ post.date | date: "%B %-d %Y" }}

{{ post.content }}

{% endunless %}
{% endunless %}
{% endfor %}