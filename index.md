---
---
# All posts

{% for project in site.posts %}
- **{{ project.title }}**
{% endfor %}

# Projects

{% for project in site.categories.projects %}
### **{{ project.title }}**
{{ project.content }}
{% endfor %}

# Team members

# News
