---
layout: default
title: Projects
---
<div class="post">
        <h1 class="pageTitle">Projects & Notes.</h1>
        <p>This is a scratch bad for things ranging from hockey to x86 ASM.</p>

                     {% for project in site.projects %}
                     <h2> <a href="{{ project.url }}">{{ project.title }}</a></h2>
                     <p>{{ project.description }}</p>
                      {% endfor %}

</div>
