---
layout: page
title: Bits and pieces...
tagline: 
---
{% include JB/setup %}

Welcome to my GitHub hosted blog/site (via jekyll).

Here, you wil find various things that I've decided to post like pieces of code I've hacked on, etc.  Most
will related to Amateur Radio.

Select from one of the posts below...

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



