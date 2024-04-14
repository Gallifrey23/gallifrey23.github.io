---
layout: default
---


<h1>My Posts</h1>
<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}.......................{{ post.date | date_to_string }}</a></h2>
    </li>
  {% endfor %}
</ul>



<h1>Latest Posts</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>