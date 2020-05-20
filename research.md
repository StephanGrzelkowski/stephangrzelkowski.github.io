--- 
layout: page
title: Research Projects
permalink: /research/
---
<pre>
{{site.posts.size | jsonify }}
{{site.posts | jsonify }}
</pre>
{%- if site.research_projects.size > 0 -%}
<ul class="post-list">
    {%- for post in site.research_projects-%}
    <li>
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
