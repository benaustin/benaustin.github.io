---
layout: page
title: Ben Austin
tagline: A Blog
---
## Welcome to my blog. 
I am working to become a web developer and everyone says that I need to create a blog so here we go... As we go along this page will change and update with new info and changes to what I've been learning. I will eventually add a portfolio as I complete projects.
    
## Blog Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## Contact
<a href="mailto:benjamin.k.austin@gmail.com">Email me</a> <a href="https://www.twitter.com/thebenaustin">Tweet Me</a>