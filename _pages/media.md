---
layout: archive
permalink: /media/
title: "Podcasts & Videos"
author_profile: true
---


{% include base_path %}


This page includes a list of media, either podcasts or videos, categorized by topic. Click on each topic to find the relevant media. 

<input type="text" id="media-search" placeholder="Search media by title..." style="width:100%; padding:8px; margin-bottom:16px; font-size:1em; border:1px solid #ccc; border-radius:4px; box-sizing:border-box;">

<script>
document.getElementById('media-search').addEventListener('input', function() {
  var query = this.value.toLowerCase();
  document.querySelectorAll('details').forEach(function(detail) {
    var items = detail.querySelectorAll('.list__item');
    var hasVisible = false;
    items.forEach(function(item) {
      var match = query === '' || item.textContent.toLowerCase().includes(query);
      item.style.display = match ? '' : 'none';
      if (match) hasVisible = true;
    });
    if (query === '') {
      detail.removeAttribute('open');
    } else if (hasVisible) {
      detail.setAttribute('open', '');
    } else {
      detail.removeAttribute('open');
    }
  });
});
</script>

<details close>
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


<details close>
<summary class="id2">
Climate Change
</summary>

{% for post in site.media reversed %}
  {% if post.category == 'climate change  ' %}
    {% include archive-single-podcasts.html %}
  {% endif %}
{% endfor %}

</details>


<details close>
<summary>
Efficiency, Market Failure, and Market Solutions
</summary>

{% for post in site.media reversed %}
  {% if post.category == 'efficiency' or post.category == 'market failure' or post.category == 'market solutions' %}
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


<details close>
<summary>
Growth and/or Development
</summary>

{% for post in site.media reversed %}
  {% if post.category == 'growth and development' %}
    {% include archive-single-podcasts.html %}
  {% endif %}
{% endfor %}

</details>



<details close>
<summary class = "id1">
Natural Resources
</summary>

{% for post in site.media reversed %}
  {% if post.category == 'natural resources' %}
    {% include archive-single-podcasts.html %}
  {% endif %}
{% endfor %}

</details>


<details close>
<summary class = "id2">
Non-market Solutions
</summary>

{% for post in site.media reversed %}
  {% if post.category == 'non-market solutions' %}
    {% include archive-single-podcasts.html %}
  {% endif %}
{% endfor %}

</details>

<details close>
<summary>
Valuation
</summary>

{% for post in site.media reversed %}
  {% if post.category == 'valuation' %}
    {% include archive-single-podcasts.html %}
  {% endif %} 
{% endfor %}

</details>
  

<details close>
<summary class = "id1">
Water
</summary>

{% for post in site.media reversed %}
  {% if post.category == 'water' %}
    {% include archive-single-podcasts.html %}
  {% endif %} 
{% endfor %}

</details>