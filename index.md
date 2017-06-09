## Welcome to Javascript WTF


{% for post in site.posts %}

## [{{post.title}}]({{post.url}})

###### {{ post.date | date_to_long_string }}

{{ post.content }}

{% endfor %}