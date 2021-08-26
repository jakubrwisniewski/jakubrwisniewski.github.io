---
layout: home
---

<section class="home-posts">
  {% for post in site.posts %}
	{% inlude post-inline.html post=post %}
  {% endfor %}
</section>
