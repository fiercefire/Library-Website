---
layout: page
title: Blog Archive
---
<link rel="stylesheet" href="css/font.css" type="text/css">

<style>
@media (prefers-color-scheme: dark) {
  body {
    background-color: #1a1a1a;
    color: #ddd;
  }

a {
  color: #99ccff;
}

img {
  filter: brightness(90%) contrast(110%);
  }
}
</style>

<div class="wrapper">
{% for tag in site.tags %}
  <h3>{{ tag[0] }}</h3>
  <ul>
    {% for post in tag[1] %}
      <li><a href="{{ post.url | relative_url }}">{{ post.date | date: "%B %d, %Y" }} - {{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}
</div>
