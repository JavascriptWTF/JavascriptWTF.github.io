{% for post in site.posts %}

{:.date}
{{ post.date | date_to_long_string }}
## [{{post.title}}]({{post.url}})

{{ post.content }}

<hr>

{% endfor %}
