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
  <summary class= "id2" > General </summary>
  <div class="content">
    <details class="sub_detail" open>
      <summary> Readings </summary>
      <div class="content">
          {% for post in site.publications reversed %}
              {% if post.category == 'general' %}
                {% include archive-single-publications.html %}
              {% endif %}
          {% endfor %}
      </div>
    </details>
    <details class="sub_detail" close>
      <summary> Activities </summary>
      <div class="content">
          {% for post in site.activities reversed %}
              {% if post.category == 'general' %}
                {% include archive-single-activities.html %}
              {% endif %}
          {% endfor %}
      </div>
    </details>
    <details class="sub_detail" close>
      <summary> Media </summary>
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
  <summary> Benefit/Cost Analysis </summary>
  <div class="content">
    <details class="sub_detail" close>
      <summary> Readings </summary>
      <div class="content">
          {% for post in site.publications reversed %}
              {% if post.category == 'benefit-cost' %}
                {% include archive-single-publications.html %}
              {% endif %}
          {% endfor %}
      </div>
    </details>
    <details class="sub_detail" close>
      <summary> Activities </summary>
      <div class="content">
          {% for post in site.activities reversed %}
              {% if post.category == 'benefit-cost' %}
                {% include archive-single-activities.html %}
              {% endif %}
          {% endfor %}
      </div>
    </details>
    <details class="sub_detail" close>
      <summary> Media </summary>
      <div class="content">
        {% for post in site.media reversed %}
          {% if post.category == 'benefit-cost' %}
            {% include archive-single-podcasts.html %}
          {% endif %}
        {% endfor %}
      </div>
    </details>

  </div>
</details>

<details open>
  <summary class = "id2"> Climate Change </summary>
  <div class="content">
    <details class="sub_detail" close>
      <summary> Readings </summary>
      <div class="content">
          {% for post in site.publications reversed %}
              {% if post.category == 'climate change' %}
                {% include archive-single-publications.html %}
              {% endif %}
          {% endfor %}
      </div>
    </details>
    <details class="sub_detail" close>
      <summary> Activities </summary>
      <div class="content">
          {% for post in site.activities reversed %}
              {% if post.category == 'climate change' %}
                {% include archive-single-activities.html %}
              {% endif %}
          {% endfor %}
      </div>
    </details>
    <details class="sub_detail" close>
      <summary> Media </summary>
      <div class="content">
        {% for post in site.media reversed %}
          {% if post.category == 'climate change' %}
            {% include archive-single-podcasts.html %}
          {% endif %}
        {% endfor %}
      </div>
    </details>

  </div>
</details>

<details open>
  <summary> Efficiency and/or Markets </summary>
  <div class="content">
    <details class="sub_detail" close>
      <summary> Readings </summary>
      <div class="content">
          {% for post in site.publications reversed %}
              {% if post.category == 'efficiency' %}
                {% include archive-single-publications.html %}
              {% endif %}
          {% endfor %}
      </div>
    </details>
    <details class="sub_detail" close>
      <summary> Activities </summary>
      <div class="content">
          {% for post in site.activities reversed %}
              {% if post.category == 'efficiency' %}
                {% include archive-single-activities.html %}
              {% endif %}
          {% endfor %}
      </div>
    </details>
    <details class="sub_detail" close>
      <summary> Media </summary>
      <div class="content">
        {% for post in site.media reversed %}
          {% if post.category == 'efficiency' %}
            {% include archive-single-podcasts.html %}
          {% endif %}
        {% endfor %}
      </div>
    </details>

  </div>
</details>