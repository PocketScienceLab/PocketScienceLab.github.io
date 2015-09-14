---
layout: default
title: Home
---

# Pocket Science Laboratory: Moving Beyond the Classroom Walls

{% include intro.md %}

[Read more...](about)


## News

{% for post in site.posts %}
{{ post.date | date_to_string }}
: [{{ post.title }}]({{ site.baseurl}}{{ post.url }})
{% endfor %}

<p>&copy; {{ site.time | date: '%Y' }}. All rights reserved.</p>
