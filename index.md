---
layout: page
comments: false
---

# Statistics Quick Reference
{% for post in site.posts reversed %}
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
