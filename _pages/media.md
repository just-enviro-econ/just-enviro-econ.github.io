---
layout: archive
permalink: /media/
title: "Podcasts & Videos"
author_profile: true
---


{% include base_path %}

This page includes a list of media, either podcasts or videos, categorized by topic. 

  <details open>
      <summary class="id1">
      Environmental Justice
      </summary>
      <p>Test 1</p>
      {% for post in site.media reversed %}
      <p>Test 2</p>
        {% if post.category == 'environmental justice' %}
          {% include archive-single-podcasts.html %}
        {% endif %}
      {% endfor %}
      
  </details>

  