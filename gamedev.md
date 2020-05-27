---
layout: page
title: GameDev
permalink: /gamedev/
height_thumbnail: 200px
---
{%- if site.games.size > 0 -%}
<ul class="post-list">
    <hr>
    <br>
    {%- for post in site.games reversed-%}
    <li>
    <img src="{{post.thumb_url}}" style="float:right;width:{{page.height_thumbnail}}">
    <h2>
        <a class="post-link" href="{{ post.url | relative_url }}">
        {{ post.title | escape }}
        </a>
    </h2>
    {%- if site.show_excerpts -%}
        {{ post.excerpt }}
        
    {%- endif -%}
    </li>
    <hr>
    <br>
    {%- endfor -%}
</ul>

{%- endif -%}
