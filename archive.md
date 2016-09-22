---
layout: page
title: Archive
---

## Blog Posts

<div id="archive">
	{% for post in site.posts %}
    <div class="card">
      <div class="profile">
        <img src="{{site.baseurl}}/public/images/author/{{post.nickname}}.jpg">
        <div class="description">
          <p class="name">{{post.author}}</p>
           <p>{{post.date | date_to_string}}</p>
        </div>
        <div class="clear"></div>
      </div>
      {% if post.coverimg %}
      <div class="cover-img">
        <img  src="{{site.baseurl}}/public/images/posts/{{post.coverimg}}.jpg"/> 
      </div>
      {% endif %}
      <a href="{{ post.url }}" class="heading">Bajra Weekly #{{ post.number }}: {{ post.title }}<br/></a>

      <p class="tag">
        <i class="fa fa-tags fa-flip-horizontal"></i> 
        {% if post.tags %}
        {% for tag in post.tags %}
        <a href="{{site.baseurl}}/tag/{{ tag }}">{{ tag }}</a>
        {% endfor %}
        {% endif %}
      </p>
    </div>
  {% endfor %}
</div>