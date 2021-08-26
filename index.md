---
layout: home
---

<section class="home-posts">
  {% for post in site.posts %}
	<article>
		<h3>
			<a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
		</h3>
		{{ post.excerpt }}
	</article>
  {% endfor %}
</section>
