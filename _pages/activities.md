---
layout: archive
title: "Activities and Teaching Advice"
permalink: /activities/
author_profile: true
---


<!-- Table 1 from paper, Course Topics: Market failure, efficiency and/or markets, climate change, market solutions, natural resources, valuation, non-market valuation, benefit/cost analysis, growth and/or development, environmental justice, population -->



{% include base_path %}

<br>

This site includes articles that describe classroom activities or teaching advice. Click on each category to find relevant material to that topic. 

<details close>
<summary>
General
</summary>

{% for post in site.activities reversed %}
    {% if post.category == 'general' %}
      {% include archive-single-activities.html %}
    {% endif %}
{% endfor %}

</details>


<details close>
<summary class="id1">
Benefit/Cost Analysis
</summary>

{% for post in site.activities reversed %}
  {% if post.category == 'benefit-cost' %}
    {% include archive-single-activities.html %}
  {% endif %}
{% endfor %}

</details>


<details close>
<summary class="id2">
Climate Change
</summary>

{% for post in site.activities reversed %}
  {% if post.category == 'climate change' %}
    {% include archive-single-activities.html %}
  {% endif %}
{% endfor %}

</details>

<details close>
<summary>
Efficiency, Market Failure, and Market Solutions
</summary>

{% for post in site.activities reversed %}
  {% if post.category == 'efficiency' or post.category == 'market failure' or post.category == 'market solutions' %}
    {% include archive-single-activities.html %}
  {% endif %}
{% endfor %}

</details>

<details close>
<summary class = "id1">
Energy
</summary>

{% for post in site.activities reversed %}
  {% if post.category == 'energy' %}
    {% include archive-single-activities.html %}
  {% endif %}
{% endfor %}

</details>

<details close>
<summary class = "id2">
Environmental Justice
</summary>

{% for post in site.activities reversed %}
    {% if post.category == 'environmental justice' %}
      {% include archive-single-activities.html %}
    {% endif %}
{% endfor %}

</details>


<details close>
<summary >
Growth and/or Development
</summary>

{% for post in site.activities reversed %}
  {% if post.type == 'pr' %}
    {% if post.category == 'growth and development' %}
    {% include archive-single-activities.html %}
    {% endif %}
  {% endif %}
{% endfor %}

</details>


<details close>
<summary class = "id1">
Natural Resources
</summary>

{% for post in site.activities reversed %}
  {% if post.type == 'pr' %}
    {% if post.category == 'natural resources' %}
    {% include archive-single-activities.html %}
    {% endif %}
  {% endif %}
{% endfor %}

</details>


<details close>
<summary class = "id2">
Non-market Solutions
</summary>

{% for post in site.activities reversed %}
  {% if post.type == 'pr' %}
    {% if post.category == 'non-market solutions' %}
    {% include archive-single-activities.html %}
    {% endif %}
  {% endif %}
{% endfor %}


</details>

<details close>
<summary>
Valuation
</summary>

{% for post in site.activities reversed %}
  {% if post.type == 'pr' %}
    {% if post.category == 'valuation' %}
    {% include archive-single-activities.html %}
    {% endif %}
  {% endif %}
{% endfor %}

</details>

<details close>
<summary class = "id1">
Water
</summary>

{% for post in site.activities reversed %}
  {% if post.type == 'pr' %}
    {% if post.category == 'water' %}
    {% include archive-single-activities.html %}
    {% endif %}
  {% endif %}
{% endfor %}

</details>