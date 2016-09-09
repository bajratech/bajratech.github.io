---
layout: page
title: Archive
---

## Blog Posts
<div id="archive">
	{% for post in site.posts %}
	<a href="{{post.url}}">
		<div class="list">

			{{ post.title }}<br/>
			<p>
				{{ post.date | date_to_string }} 
			</p>
			<p class="tag">
				<span>Tags:</span> 
				{% if post.tags %}
				{% for tag in post.tags %}
				<a href="{{site.baseurl}}/tag/{{ tag }}">{{ tag }}</a>
				{% endfor %}
				{% endif %}
			</p>
			<p>
				{% if post.author %}
				Author: {{post.author}}
				{% endif %}
			</p>


		</div>
	</a>
	{% endfor %}
</div>