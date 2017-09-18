---
layout: page
title: Work
sitemap: true
---

## Some of the things I've done. 

Read more about my talks and [projects](https://github.com/xolian).

<h2>Talks</h2>
<ul class="related-posts">
  {% for post in site.categories.talk %}
    <li>
      <h3>
        <a href="{{ post.url }}">
          {{ post.venue }}
          <small>{{ post.title }}</small>
        </a>
      </h3>
    </li>
  {% endfor %}
</ul>

<h2>Open-Source Projects</h2>
<ul class="related-posts">
  {% for post in site.categories.disclosure %}
    <li>
      <h3>
        <a href="{{ post.url }}">
          {{ post.product }}
          <small>{{ post.vulnerability }}</small>
        </a>
      </h3>
    </li>
  {% endfor %}
</ul>
