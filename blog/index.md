---
layout: default
title: Blog
nav: yes
excerpt: Meta description goes here
bg: "#111 url('/images/mt-elbert.jpg') no-repeat top center; background-size: cover;"
---
<div class="page-heading">
    <h1>Archive</h1>
</div>

<div class="wrapper">


  <ul class="post-list">
    {% for post in site.posts %}
      <li class="row centered card"  onclick="location.href='{{ post.url | prepend: site.baseurl }}';">
            <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>
            <div class="col-8">
                <h2>{{ post.title }}</h2>
                <h5>Tags: {% if post.tags %}{{ post.tags | join: ', ' }}{% endif %}</h5>
                <div class="entry-content">{{ post.excerpt }}&hellip;</div>
                <p><a href="{{ post.url | prepend: site.baseurl }}">Read More</a></p>
            </div>
      </li>
    {% endfor %}
  </ul>

  <p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p>

</div>



{% assign post = site.posts.first %}
{% assign content = post.content %}
<div class="row centered card" onclick="location.href='{{ root_url }}{{ post.url }}';">
    <div class="col-4">
        <div id="post-img"></div>
        <!-- <img src="{{ post.archive-img }}" /> -->
    </div>
    <div class="col-8">
        <h2>{{ post.title }}</h2>
        <h5>Tags: {% if post.tags %}{{ post.tags | join: ', ' }}{% endif %}</h5>
        <div class="entry-content">{{ post.excerpt }}&hellip;</div>
        <p><a href="{{ root_url }}{{ post.url }}">Read More</a></p>
    </div>
</div>