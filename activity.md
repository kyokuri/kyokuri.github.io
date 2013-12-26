---
layout: page
title: 活動について
page: activity
---

小中学生向けのワークショップを関西を中心に開催しています。 

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
