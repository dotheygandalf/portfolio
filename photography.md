---
layout: default
title: Photography
permalink: /photography/
---

<div class="wrapper">
  <ul class="photography-list">
    {% assign sortedTitles = site.photography | sort: 'title' %}
    {% for post in sortedTitles %}
      <li>
        <a href="{{ post.url | prepend: site.baseurl }}">
          <img class="post-left" src="{{ post.thumbnail }}" />
        </a>
        <div class="post-right">
          <h1 class="post-link">
            <a href="{{ post.url | prepend: site.baseurl }}">// {{ post.title }} //</a>
          </h1>
        </div>
      </li>
    {% endfor %}
  </ul>
</div>
