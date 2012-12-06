---
layout: page
title: Improvment Through Service
tagline: Living to serve
---
{% include JB/setup %}

 
## More to come soon

In the near future, I will begin posting things I've learned and scripts I've written while running enterprise systems in support of online learning over the last decade.

Mental Meanderings:

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



