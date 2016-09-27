---
layout: default
title: projects
---

{% include header.html %}
<div class="project">
    <ul>
        {% for item in site.data.projects.ongoing %}
        <li>
        <h2><a href="{{item.source}}"> {{ item.title }}</a></h2>
        <h3>{{ item.description }}</h3>
        <p>{{ item.brief }}</p>


        </li>
        {% endfor %}
    </ul>
</div>
