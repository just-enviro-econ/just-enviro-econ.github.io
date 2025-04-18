---
layout: archive
title: "Syllabus"
permalink: /syllabus/
author_profile: true
redirect_from:
  - /syllabus
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

<details open>
  <summary class = "id2"> Environmental Justice </summary>
  <div class="content">
    <details class="sub_detail" close>
      <summary> Readings </summary>
      <div class="content">
          {% for post in site.publications reversed %}
              {% if post.category == 'environmental justice' %}
                {% include archive-single-publications.html %}
              {% endif %}
          {% endfor %}
      </div>
    </details>
    <details class="sub_detail" close>
      <summary> Activities </summary>
      <div class="content">
          {% for post in site.activities reversed %}
              {% if post.category == 'environmental justice' %}
                {% include archive-single-activities.html %}
              {% endif %}
          {% endfor %}
      </div>
    </details>
    <details class="sub_detail" close>
      <summary> Media </summary>
      <div class="content">
        {% for post in site.media reversed %}
          {% if post.category == 'environmental justice' %}
            {% include archive-single-podcasts.html %}
          {% endif %}
        {% endfor %}
      </div>
    </details>

  </div>
</details>

<details open>
  <summary> Growth and/or Development </summary>
  <div class="content">
    <details class="sub_detail" close>
      <summary> Readings </summary>
      <div class="content">
          {% for post in site.publications reversed %}
              {% if post.category == 'growth and development' %}
                {% include archive-single-publications.html %}
              {% endif %}
          {% endfor %}
      </div>
    </details>
    <details class="sub_detail" close>
      <summary> Activities </summary>
      <div class="content">
          {% for post in site.activities reversed %}
              {% if post.category == 'growth and development' %}
                {% include archive-single-activities.html %}
              {% endif %}
          {% endfor %}
      </div>
    </details>
    <details class="sub_detail" close>
      <summary> Media </summary>
      <div class="content">
        {% for post in site.media reversed %}
          {% if post.category == 'growth and development' %}
            {% include archive-single-podcasts.html %}
          {% endif %}
        {% endfor %}
      </div>
    </details>

  </div>
</details>

<details open>
  <summary class = "id2"> Market Failure </summary>
  <div class="content">
    <details class="sub_detail" close>
      <summary> Readings </summary>
      <div class="content">
          {% for post in site.publications reversed %}
              {% if post.category == 'market failure' %}
                {% include archive-single-publications.html %}
              {% endif %}
          {% endfor %}
      </div>
    </details>
    <details class="sub_detail" close>
      <summary> Activities </summary>
      <div class="content">
          {% for post in site.activities reversed %}
              {% if post.category == 'market failure' %}
                {% include archive-single-activities.html %}
              {% endif %}
          {% endfor %}
      </div>
    </details>
    <details class="sub_detail" close>
      <summary> Media </summary>
      <div class="content">
        {% for post in site.media reversed %}
          {% if post.category == 'market failure' %}
            {% include archive-single-podcasts.html %}
          {% endif %}
        {% endfor %}
      </div>
    </details>

  </div>
</details>

<details open>
  <summary> Market Solutions </summary>
  <div class="content">
    <details class="sub_detail" close>
      <summary> Readings </summary>
      <div class="content">
          {% for post in site.publications reversed %}
              {% if post.category == 'market solutions' %}
                {% include archive-single-publications.html %}
              {% endif %}
          {% endfor %}
      </div>
    </details>
    <details class="sub_detail" close>
      <summary> Activities </summary>
      <div class="content">
          {% for post in site.activities reversed %}
              {% if post.category == 'market solutions' %}
                {% include archive-single-activities.html %}
              {% endif %}
          {% endfor %}
      </div>
    </details>
    <details class="sub_detail" close>
      <summary> Media </summary>
      <div class="content">
        {% for post in site.media reversed %}
          {% if post.category == 'market solutions' %}
            {% include archive-single-podcasts.html %}
          {% endif %}
        {% endfor %}
      </div>
    </details>

  </div>
</details>

<details open>
  <summary class = "id2"> Natural Resources </summary>
  <div class="content">
    <details class="sub_detail" close>
      <summary> Readings </summary>
      <div class="content">
          {% for post in site.publications reversed %}
              {% if post.category == 'natural resources' %}
                {% include archive-single-publications.html %}
              {% endif %}
          {% endfor %}
      </div>
    </details>
    <details class="sub_detail" close>
      <summary> Activities </summary>
      <div class="content">
          {% for post in site.activities reversed %}
              {% if post.category == 'natural resources' %}
                {% include archive-single-activities.html %}
              {% endif %}
          {% endfor %}
      </div>
    </details>
    <details class="sub_detail" close>
      <summary> Media </summary>
      <div class="content">
        {% for post in site.media reversed %}
          {% if post.category == 'natural resources' %}
            {% include archive-single-podcasts.html %}
          {% endif %}
        {% endfor %}
      </div>
    </details>

  </div>
</details>

<details open>
  <summary> Non-market Solutions </summary>
  <div class="content">
    <details class="sub_detail" close>
      <summary> Readings </summary>
      <div class="content">
          {% for post in site.publications reversed %}
              {% if post.category == 'non-market solutions' %}
                {% include archive-single-publications.html %}
              {% endif %}
          {% endfor %}
      </div>
    </details>
    <details class="sub_detail" close>
      <summary> Activities </summary>
      <div class="content">
          {% for post in site.activities reversed %}
              {% if post.category == 'non-market solutions' %}
                {% include archive-single-activities.html %}
              {% endif %}
          {% endfor %}
      </div>
    </details>
    <details class="sub_detail" close>
      <summary> Media </summary>
      <div class="content">
        {% for post in site.media reversed %}
          {% if post.category == 'non-market solutions' %}
            {% include archive-single-podcasts.html %}
          {% endif %}
        {% endfor %}
      </div>
    </details>

  </div>
</details>

<details open>
  <summary class = "id2"> Valuation </summary>
  <div class="content">
    <details class="sub_detail" close>
      <summary> Readings </summary>
      <div class="content">
          {% for post in site.publications reversed %}
              {% if post.category == 'valuation' %}
                {% include archive-single-publications.html %}
              {% endif %}
          {% endfor %}
      </div>
    </details>
    <details class="sub_detail" close>
      <summary> Activities </summary>
      <div class="content">
          {% for post in site.activities reversed %}
              {% if post.category == 'valuation' %}
                {% include archive-single-activities.html %}
              {% endif %}
          {% endfor %}
      </div>
    </details>
    <details class="sub_detail" close>
      <summary> Media </summary>
      <div class="content">
        {% for post in site.media reversed %}
          {% if post.category == 'valuation' %}
            {% include archive-single-podcasts.html %}
          {% endif %}
        {% endfor %}
      </div>
    </details>

  </div>
</details>