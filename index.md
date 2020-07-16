---
layout: default 
---

# Welcome to HILA 561: The Spanish Inquisition {#history}

### recent posts {#history}

<ul>
  {% for post in site.posts %}
    <li>
      <a href="/561-Inquisition{{ post.url }}">{{ post.title }}</a>  
      <br>
      {{ post.date | date: '%B %d, %Y' }}

      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
