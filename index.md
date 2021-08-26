---
layout: home
---

<section>
  {% for post in site.posts %}
	<article>
		<h3>
			<a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
		</h3>
		<p>{{ post.content }}</p>
	</article>
  {% endfor %}
</section>
