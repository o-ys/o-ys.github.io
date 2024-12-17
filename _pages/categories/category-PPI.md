---
 title: "PPI"
 layout: archive
 permalink: categories/PPI
 author_profile: true
 sidebar:
   nav: "docs"
 ---

 {% assign posts = site.categories.categories %}
 {% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}
