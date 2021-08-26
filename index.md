---
layout: home
---

<section class="home-posts">
  {% for post in site.posts %}
	<article>
		<h3>
			<a href="{{ post.url }}">{{ post.title }}</a>
		</h3>
		{% include tags.html tags=post.tags %}
		{{ post.content }}
	</article>
  {% endfor %}
</section>
