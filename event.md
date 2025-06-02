---
layout: page
Title: ""

---
<h1>Posts</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> — <small>{{ post.date | date: "%B %d, %Y" }}</small><br/>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
