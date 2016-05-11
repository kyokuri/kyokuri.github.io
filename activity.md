---
layout: page
title: 活動について
page: activity
---

小中学生向けのワークショップを関西を中心に開催しています。

### これまでのイベント

<ul>
  <li><a href="/scratchday2016/">Scratch Day 2016 in いちょう祭</a></li>
  <li><a href="/scratchday2015/">Scratch Day 2015 in Kansai</a></li>
  <li><a href="/ichosai2015/">いちょう祭 2015</a></li>
  <li><a href="/ichosai2014/">いちょう祭 2014</a></li>
  <li><a href="/scratchday2014/">Scratch Day 2014 in Osaka</a></li>
</ul>

### これまでの活動

<ul class="posts">
  {% for post in site.posts %}
    <li class="post">
      <p class="post-category">
        {% if post.category %}
          <img src="/images/label-{{ post.category }}.png">
        {% endif %}
      </p>
      <p class="post-info">
        <a href="{{ post.url }}">{{ post.title }}</a>
        <time>{{ post.date | date: "%Y/%m/%d" }}</time>
      </p>
    </li>
  {% endfor %}
</ul>
