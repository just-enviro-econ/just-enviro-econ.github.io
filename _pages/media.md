---
layout: archive
permalink: /media/
title: "Podcasts & Videos"
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

{% include base_path %}


This page includes a list of media, either podcasts or videos, categorized by topic.


<details open>
<summary>
General
</summary>

{% for post in site.media reversed %}
    {% if post.category == 'general' %}
      {% include archive-single-podcasts.html %}
    {% endif %}
{% endfor %}

</details>


<details open>
<summary class="id1">
Benefit/Cost Analysis
</summary>

{% for post in site.media reversed %}
  {% if post.category == 'benefit-cost' %}
    {% include archive-single-podcasts.html %}
  {% endif %}
{% endfor %}

</details>


<details open>
<summary class="id2">
Climate Change
</summary>

{% for post in site.media reversed %}
  {% if post.category == 'climate change  ' %}
    {% include archive-single-podcasts.html %}
  {% endif %}
{% endfor %}

</details>


<details open>
<summary>
Efficiency and/or Markets
</summary>

{% for post in site.media reversed %}
  {% if post.category == 'efficiency' %}
    {% include archive-single-podcasts.html %}
  {% endif %}
{% endfor %}

</details>

<details close>
<summary class = "id1">
Energy
</summary>

{% for post in site.media reversed %}
  {% if post.category == 'energy' %}
    {% include archive-single-podcasts.html %}
  {% endif %}
{% endfor %}

</details>

<details close>
<summary class = "id2">
Environmental Justice
</summary>

{% for post in site.media reversed %}
    {% if post.category == 'environmental justice' %}
      {% include archive-single-podcasts.html %}
    {% endif %}
{% endfor %}

</details>


<details open>
<summary>
Growth and/or Development
</summary>

{% for post in site.media reversed %}
  {% if post.category == 'growth and development' %}
    {% include archive-single-podcasts.html %}
  {% endif %}
{% endfor %}

</details>

<details open>
<summary class = "id1">
Market Failure
</summary>

{% for post in site.media reversed %}
  {% if post.category == 'market failure' %}
    {% include archive-single-podcasts.html %}
  {% endif %}
{% endfor %}

</details>

<details open>
<summary class="id2">
Market Solutions
</summary>

{% for post in site.media reversed %}
  {% if post.category == 'market solutions' %}
    {% include archive-single-podcasts.html %}
  {% endif %}
{% endfor %}

</details>

<details open>
<summary>
Natural Resources
</summary>

{% for post in site.media reversed %}
  {% if post.category == 'natural resources' %}
    {% include archive-single-podcasts.html %}
  {% endif %}
{% endfor %}

</details>


<details open>
<summary class = "id1">
Non-market Solutions
</summary>

{% for post in site.media reversed %}
  {% if post.category == 'non-market solutions' %}
    {% include archive-single-podcasts.html %}
  {% endif %}
{% endfor %}

</details>

<details open>
<summary class="id2">
Valuation
</summary>

{% for post in site.media reversed %}
  {% if post.category == 'valuation' %}
    {% include archive-single-podcasts.html %}
  {% endif %} 
{% endfor %}

</details>
  

<details open>
<summary>
Water
</summary>

{% for post in site.media reversed %}
  {% if post.category == 'water' %}
    {% include archive-single-podcasts.html %}
  {% endif %} 
{% endfor %}

</details>