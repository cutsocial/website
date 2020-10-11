---
title:
heading: Cut the Cake
list_title: ' '
---


<div class="demo-container">
  <iframe src="https://lens.cut.social/#/mad2020a/en" frameborder="0" allowfullscreen=""></iframe>
</div>



  {%- if posts.size > 0 -%}
    {%- if page.list_title -%}
      <h2 class="post-list-heading">{{ page.list_title }}</h2>
    {%- endif -%}
    <ul class="post-list">
      {%- assign date_format = site.minima.date_format | default: "%b %-d, %Y" -%}
      {%- for post in posts -%}
        {%- if forloop.first == true -%}
        <li>
          <h3>
            <a class="post-link" href="{{ post.url | relative_url }}">
              {{ post.title | escape }}
            </a>
          </h3>
          {%- if site.show_excerpts -%}
            {{ post.excerpt }}
          {%- endif -%}
        </li>
        {%- endif -%}
      {%- endfor -%}
    </ul>

  {%- endif -%}
