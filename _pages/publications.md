---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<!-- Table 1 from paper, Course Topics: Market failure, efficiency and/or markets, climate change, market solutions, natural resources, valuation, non-market valuation, benefit/cost analysis, growth and/or development, environmental justice, population -->



{% include base_path %}

<br>

<details open>
<summary>
Natural Resources
</summary>

{% for post in site.publications reversed %}
    {% if post.category == 'natural resources' %}
      {% include archive-single-publications.html %}
    {% endif %}
{% endfor %}

</details>


<details open>
<summary class="id1">
Climate Change
</summary>

{% for post in site.publications reversed %}
  {% if post.category == 'climate change' %}
    {% include archive-single-publications.html %}
  {% endif %}
{% endfor %}

</details>


<details open>
<summary class="id2">
Classroom Activities 
</summary>

{% for post in site.publications reversed %}
  {% if post.type == 'pr' %}
    {% if post.category == 'pedagogy' %}
    {% include archive-single-publications.html %}
    {% endif %}
  {% endif %}
{% endfor %}

</details>




