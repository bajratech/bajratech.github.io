---
layout: post
title: Getting Started with Bajra Weekly
comments: true
---


- Clone the repo <a href="https://github.com/bajratech/bajratech.github.io.git" target="_blank">Bajra Weekly</a> and create a new relevant branch
- To create a new post, all you need to do is create a file in the **`_posts`** directory
- Bajra Weekly requires blog post files to be named according to the following format:
```
YEAR-MONTH-DAY-title.MARKUP
```
- Write your blog in previously created file. It is motivated to write your blogs on **`markdown`**
- Once you are done, you can push it to the repo and submit a pull request
- You should submit your pull request to **`Loomila Hada`**	

<div class="author">
  <div>
  <span class="title">Author</span><br/>
  <span class="name">Ankur Maharjan</span>

  </div>
  <div>
  <img src="{{site.baseurl}}/public/images/author/ankur.jpg">
</div>

</div>

<div class="clear"></div>

-----

Want to see something else added? <a href="https://github.com/poole/poole/issues/new">Open an issue.</a>


-----
{% if page.comments %}
<div id="disqus_thread"></div>
<script>

/**
 *  RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
 *  LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables */
/*
var disqus_config = function () {
    this.page.url = PAGE_URL;  // Replace PAGE_URL with your page's canonical URL variable
    this.page.identifier = PAGE_IDENTIFIER; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
};
*/
(function() { // DON'T EDIT BELOW THIS LINE
    var d = document, s = d.createElement('script');
    s.src = '//bajratechnologies.disqus.com/embed.js';
    s.setAttribute('data-timestamp', +new Date());
    (d.head || d.body).appendChild(s);
})();
{% endif %}

