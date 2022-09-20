---
title: Ankit Kumar Gupta
---

# Collections
{% for book in collection.books %}
  <h2>{{ book.name }} - {{ book.position }}</h2>
  <p>{{ book.content | markdownify }}</p>
{% endfor %}
