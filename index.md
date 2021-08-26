---
layout: home
---

<section class="home-posts">
  {% for post in site.posts %}
	{% include inline/post.html post=post %}
  {% endfor %}
</section>
