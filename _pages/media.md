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
      <summary class="id1">
      Environmental Justice
      </summary>
      {% for post in site.media reversed %}
        {% if post.category == 'environmental justice' %}
          {% include archive-single-podcasts.html %}
        {% endif %}
      {% endfor %}    
  </details>

  