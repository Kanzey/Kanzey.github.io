---
title: Simpole static blog
---

{% for post in site.posts %}
    * [ {{ post.title }} ]( {{ post.url }} )
{% endfor %}
