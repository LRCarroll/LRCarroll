---
layout: post
title: Tongariro Northern Circuit
tags: Test Code
published: true
---



This is a test link: 
<ul>
  {% for post in site.posts %}  
    <li>
      <a href="Website/{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

[Project 1]({{ site.baseurl }}{% link _posts/2022-01-06-TongariroNC.md %})


