---
layout: page
title: YiLong He
tagline:
---
{% include JB/setup %}

<div class="span8" id="main-content">
  <div class="posts-index">
    {% for post in site.posts %}
        <div class='post'>
          <h2 class='post-title'>
            <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>
          </h2>
          <div class='post-content'>
            {{ post.content }}
            <em>Writed by: 中YiLong He, Published on: {{ post.date | date_to_string }}</em> | <a href="{{ BASE_PATH }}{{ post.url }}">Leave a reply</a>
          </div>
        </div>
    {% endfor %}
  </div>
</div>
