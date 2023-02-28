--- 
layout: page
title: Portfolio
permalink: /portfolio/
height_logo: 100px
---
{%- if site.portfolio.size > 0 -%}
<ul class="post-list">
    {%- for post in site.portfolio reversed-%}
    <li>
    <img src="{{post.logo_url}}" style="float:right;width:{{page.height_logo}}">
    <h2>
        <a class="post-link" href="{{ post.url | relative_url }}">
        {{ post.title | escape }}
        </a>
    </h2>
    {%- if site.show_excerpts -%}
        {{ post.excerpt }}
        
    {%- endif -%}
    </li>
    {%- endfor -%}
</ul>

{%- endif -%}
