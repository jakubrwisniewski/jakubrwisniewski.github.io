---
layout: home
---

<section class="home-posts">
  {% for post in site.posts %}
	{% include post-inline.html post=post %}
  {% endfor %}
</section>
