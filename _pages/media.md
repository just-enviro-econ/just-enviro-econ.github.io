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

<h2>Search Media</h2>
<input
  type="text"
  id="search-bar"
  placeholder="Search podcasts or videos"
  style="width:100%; padding:10px; font-size:1.1em; margin-bottom:20px;"
>

<p>This page includes a list of media, either podcasts or videos, categorized by topic.</p>


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
  

<!-- ========================= -->
<!-- Simple search script -->
<!-- ========================= -->
<script>
document.getElementById("search-bar").addEventListener("input", function() {
  const query = this.value.toLowerCase();

  // Select all podcast containers; adjust selector if needed
  const posts = document.querySelectorAll("details .archive__item");

  posts.forEach(post => {
    const text = post.textContent.toLowerCase();
    post.style.display = text.includes(query) ? "" : "none";
  });

  // Optional: hide <details> if all children are hidden
  document.querySelectorAll("details").forEach(detail => {
    const visiblePosts = detail.querySelectorAll(".archive__item:not([style*='display: none'])");
    detail.style.display = visiblePosts.length ? "" : "none";
  });
});
</script>