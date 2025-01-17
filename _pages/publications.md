---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<!-- Table 1 from paper, Course Topics: Market failure, efficiency and/or markets, climate change, market solutions, natural resources, valuation, non-market valuation, benefit/cost analysis, growth and/or development, environmental justice, population -->



{% include base_path %}

<br>

<<<<<<< HEAD
# __Natural Resources__

=======
# __Peer-Reviewed Journal Articles__
Hola soy Fidel 
>>>>>>> df4244362dd2739e5a77f51eb2c8db7f873950ba
<details open>
<summary>
Natural Resources
</summary>

{% for post in site.publications reversed %}
  {% if post.type == 'pr' %}
      {% if post.topic == 'Natural Resources' %}
      {% include archive-single-publications.html %}
      {% endif %}
  {% endif %}
{% endfor %}

</details>


<details open>
<summary class="id1">
Games and Experiments
</summary>

{% for post in site.publications reversed %}
  {% if post.type == 'pr' %}
    {% if post.category == 'games' %}
    {% include archive-single-publications.html %}
    {% endif %}
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




