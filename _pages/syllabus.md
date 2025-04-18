---
layout: archive
title: "Syllabus"
permalink: /syllabus/
author_profile: true
redirect_from:
  - /syllabus
---

{% include base_path %}

This page lists all the resources by topic. 

<details open>
  <summary> General </summary>
  <div class="content">

    <details class="sub_detail">
      <summary class="id3"> Readings </summary>
      <div class="content">
          {% for post in site.publications reversed %}
              {% if post.category == 'general' %}
                {% include archive-single-publications.html %}
              {% endif %}
          {% endfor %}
      </div>
    </details>

    <details class="sub_detail" open>
      <summary> Activities </summary>
      <div class="content">
          {% for post in site.activities reversed %}
              {% if post.category == 'general' %}
                {% include archive-single-activities.html %}
              {% endif %}
          {% endfor %}
      </div>
    </details>

    <details class="sub_detail">
      <summary class="id3"> Media </summary>
      <div class="content">
        {% for post in site.media reversed %}
          {% if post.category == 'general' %}
            {% include archive-single-podcasts.html %}
          {% endif %}
        {% endfor %}
      </div>
    </details>

  </div>
</details>

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

<details open>
<summary class = "id1">
Environmental Justice
</summary>

{% for post in site.media reversed %}
    {% if post.category == 'environmental justice' %}
      {% include archive-single-podcasts.html %}
    {% endif %}
{% endfor %}

</details>


<details open>
<summary class="id2">
Growth and/or Development
</summary>

{% for post in site.media reversed %}
  {% if post.category == 'growth and development' %}
    {% include archive-single-podcasts.html %}
  {% endif %}
{% endfor %}

</details>

<details open>
<summary>
Market Failure
</summary>

{% for post in site.media reversed %}
  {% if post.category == 'market failure' %}
    {% include archive-single-podcasts.html %}
  {% endif %}
{% endfor %}

</details>

<details open>
<summary class="id1">
Market Solutions
</summary>

{% for post in site.media reversed %}
  {% if post.category == 'market solutions' %}
    {% include archive-single-podcasts.html %}
  {% endif %}
{% endfor %}

</details>

<details open>
<summary class="id2">
Natural Resources
</summary>

{% for post in site.media reversed %}
  {% if post.category == 'natural resources' %}
    {% include archive-single-podcasts.html %}
  {% endif %}
{% endfor %}

</details>


<details open>
<summary>
Non-market Solutions
</summary>

{% for post in site.media reversed %}
  {% if post.category == 'non-market solutions' %}
    {% include archive-single-podcasts.html %}
  {% endif %}
{% endfor %}

</details>

<details open>
<summary class="id1">
Valuation
</summary>

{% for post in site.media reversed %}
  {% if post.category == 'valuation' %}
    {% include archive-single-podcasts.html %}
  {% endif %} 
{% endfor %}

</details>
  
