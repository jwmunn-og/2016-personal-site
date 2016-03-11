---
layout: default
title: Blog
nav: yes
excerpt: Blog post archive.
bg: "#f7a94f url('/images/st-helens.jpg') no-repeat top center; background-size: cover;"
---
<div class="page-heading">
    <h1>Archive</h1>
</div>
<div class="wrapper">
    <ul class="post-list">
    {% for post in site.posts %}
      <li class="row centered card"  onclick="location.href='{{ post.url | prepend: site.baseurl }}';">
            <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>
            <div class="col-4">
                
                <img src="{{ post.archive-img }}" />
            </div>
            <div class="col-8">
                <h2>{{ post.title }}</h2>
                <h5>Tags: {% if post.tags %}{{ post.tags | join: ', ' }}{% endif %}</h5>
                <div class="mob-hide">
                    <div class="entry-content">{{ post.excerpt }}&hellip;</div>
                    <p><a href="{{ post.url | prepend: site.baseurl }}">Read More</a></p>
                </div>
            </div>
      </li>
    {% endfor %}
  </ul>
</div>