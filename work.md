---
layout: default
title: Work
permalink: /work/
---

<div class="wrapper">
  <ul class="post-list">
    {% for post in site.posts %}
      <li>
        <a href="{{ post.url | prepend: site.baseurl }}">
          <img class="post-left" src="{{ post.thumbnail }}" />
        </a>
        <div class="post-right">
          <h1 class="post-link">
            <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
          </h1>
          <div class="post-details">
            <p class="post-caption">
              {{ post.caption }}
            </p>
            <p>
              {{ post.intro }}
            </p>
          </div>
        </div>
      </li>
    {% endfor %}
  </ul>
</div>
