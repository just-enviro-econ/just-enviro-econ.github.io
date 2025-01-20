---
layout: archive
title: "Readings and Publications"
permalink: /publications/
author_profile: true
---

<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-8CEVZ95BRH"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-8CEVZ95BRH');
</script>

<!-- Table 1 from paper, Course Topics: Market failure, efficiency and/or markets, climate change, market solutions, natural resources, valuation, non-market valuation, benefit/cost analysis, growth and/or development, environmental justice, population -->



{% include base_path %}

<br>

<details open>
<summary>
General
</summary>

{% for post in site.publications reversed %}
    {% if post.category == 'general' %}
      {% include archive-single-publications.html %}
    {% endif %}
{% endfor %}

</details>


<details open>
<summary class="id1">
Efficiency and/or Markets
</summary>

{% for post in site.publications reversed %}
  {% if post.category == 'efficiency' %}
    {% include archive-single-publications.html %}
  {% endif %}
{% endfor %}

</details>


<details open>
<summary class="id2">
Natural Resources
</summary>

{% for post in site.publications reversed %}
  {% if post.type == 'pr' %}
    {% if post.category == 'natural resources' %}
    {% include archive-single-publications.html %}
    {% endif %}
  {% endif %}
{% endfor %}

</details>

<details open>
<summary>
Environmental Justice
</summary>

{% for post in site.publications reversed %}
    {% if post.category == 'environmental justice' %}
      {% include archive-single-publications.html %}
    {% endif %}
{% endfor %}

</details>




