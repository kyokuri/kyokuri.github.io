---
layout: default
title: 活動について
page: activity
---

小中学生向けのワークショップを関西を中心に開催しています。 

[活動予定カレンダー](http://www.google.com/calendar/embed?src=ue7cgj644t8h04m0gbilgfe5ls%40group.calendar.google.com&ctz=Asia/Tokyo)

### これまでの活動
<ul>
	{% for post in site.posts %}
		<li><time>{{ post.date | date_to_string }}</time> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
	{% endfor %}
</ul>

