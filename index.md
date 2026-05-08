---
---

# This is not a real blog


{% for post in site.data.contentful.post.post %}

# {{ post.title }}

{{ post.body | rich_text }}

<pre>
{{ post | jsonify }}
</pre>

{% endfor %}
