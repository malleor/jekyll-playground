---
---
# All posts

+++

Posts? {% if site.total_posts == 0 %} NO {% else %} YES, {{ site.total_posts }} {% endif %}

{% for project in site.posts %}
- AAA
{% endfor %}

+++

# Projects

+++

{% for project in site.categories.projects %}
- **{{ project.title }}** -- {{ project.content }}
{% endfor %}

+++

# Team members

# News
