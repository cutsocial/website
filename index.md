---
title:
layout: default
heading: Cut the Cake
list_title: ' '
---


<div class="demo-container">
  <iframe src="https://lens.cut.social/#/mad2020a/en" frameborder="0" allowfullscreen=""></iframe>
</div>

<br /><br />
<hr class="divider" />

  {%- if page.list_title -%}
    <h2 class="post-list-heading">{{ page.list_title }}</h2>
  {%- endif -%}

  {% assign posts = site.posts %}
  {% assign latest_post = posts[0] %}
  {%- assign date_format = site.minima.date_format | default: "%b %-d, %Y" -%}

  <ul class="post-list">
    <li>
      <h2>
        <a class="post-link" href="{{ post.url | relative_url }}">
          {{ latest_post.title | escape }}
        </a>
      </h2>
      {{ latest_post.excerpt }}
    </li>

    {%- for post in posts offset:1 -%}
    <li>
      <h4>
        <a class="post-link" href="{{ post.url | relative_url }}">
          {{ post.title | escape }}
        </a>
      </h4>
    </li>
    {%- endfor -%}
    </ul>
