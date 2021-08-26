---
layout: home
---

<section class="home-posts">
  {% for post in site.posts %}
	<article>
		<h3>
			<a href="{{ post.url }}">{{ post.title }}</a>
		</h3>
		{{ post.content }}
	</article>
  {% endfor %}
</section>
