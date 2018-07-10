---
layout: blog
title: teolandon's blog
category: blog
---

Mostly ramblings, things that I notice, things that annoy me and
not-so-well-thought-out conspiracy theories about obsolete programs from the
early 2000s.

<hr>

<div class="blog-div">
  <ul class="blog-list">
    {% for post in site.posts %}
      <li class="blog-entry">
        <a href="{{ post.url }}">
          <div class="blog-title">{{ post.title }}</div>
        </a>
        <div class="post-excerpt">
          <p>
            {{ post.excerpt | strip_html }}...
          </p>
        </div>
      </li>
    {% endfor %}
  </ul>
</div>
