---
layout: default
title: Photography
permalink: /photography/
---

<div class="wrapper">
  <ul class="post-list">
    {% for post in site.photography %}
      <li>
        <a href="{{ post.url | prepend: site.baseurl }}">
          <img class="post-left" src="{{ post.thumbnail }}" />
        </a>
        <div class="post-right">
          <h1 class="post-link">
            <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
          </h1>
        </div>
      </li>
    {% endfor %}
  </ul>
</div>
