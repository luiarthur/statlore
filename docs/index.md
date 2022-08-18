---
layout: page
---

# Topics
{% for post in site.posts %}
<div class="post-preview">
    <a href="{{ post.url | prepend: site.baseurl }}">
        &raquo; {{ post.title }}
        {% if post.subtitle %}
        &mdash;
        {{ post.subtitle }}
        {% endif %}
    </a>
</div>
{% endfor %}


[1]: https://help.github.com/articles/creating-project-pages-manually
