---
layout: page
title: 活動について
page: activity
---

小中学生向けのワークショップを関西を中心に開催しています。 

[活動予定カレンダー](http://www.google.com/calendar/embed?src=ue7cgj644t8h04m0gbilgfe5ls%40group.calendar.google.com&ctz=Asia/Tokyo)

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
