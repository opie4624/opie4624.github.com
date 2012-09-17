---
layout: page
title: Down To This
tagline: You get the ankles and I'll get the wrists
---
{% include JB/setup %}
# Intros
Hi. Many know me as Opie. I'm a programmer, infosec geek, motorcycle rider, and drinker of frou-frou coffees. I mostly post longer form stuff here when I need to dump it from my brain. More often than here, I'm on the sites linked &nearrow; there. And now, I present some reading materials

<a href="{{ BASE_PATH }}{{ site.posts.first.url }}"><h2>{{ site.posts.first.title }}</h2></a>

{% if site.posts.first.excerpt %}
  {{ site.posts.first.excerpt | markdownify }} 
  <a href="{{ BASE_PATH }}{{ site.posts.first.url }}">Read More</a>
{% else %}
  {{ site.posts.first.content }}
{% endif %}

<hr width="30%">
{% include recent.html %}