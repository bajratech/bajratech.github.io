---
layout: page
title: Archive
---

## Blog Posts
<div id="archive">
	{% for post in site.posts %}
	<a href="{{post.url}}">
		<div class="list">

			Bajra Weekly #{{ post.number }}: {{ post.title }}<br/>
			<p>
				{{ post.date | date_to_string }}
				&nbsp; &nbsp;
				{% if post.author %}
				<i class="fa fa-user"></i> {{post.author}}
				{% endif %}
			</p>

			<p class="tag">
				<i class="fa fa-tags fa-flip-horizontal"></i> 
				{% if post.tags %}
				{% for tag in post.tags %}
				<a href="{{site.baseurl}}/tag/{{ tag }}">{{ tag }}</a>
				{% endfor %}
				{% endif %}
			</p>
		</div>
	</a>

	{% endfor %}
</div>