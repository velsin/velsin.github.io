---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Home
---

# Hello world
Hello world, displaying title: {{ page.title }}

{% if page.show_sidebar %}
    <div class="sidebar">
        sidebar content
    </div>
{% endif %}