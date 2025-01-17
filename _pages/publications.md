---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---




{% include base_path %}

<br>

# __Peer-Reviewed Journal Articles__
Hola soy Fidel 
<details open>
<summary>
Readings
</summary>

{% for post in site.publications reversed %}
  {% if post.type == 'pr' %}
      {% if post.category == 'research' %}
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




