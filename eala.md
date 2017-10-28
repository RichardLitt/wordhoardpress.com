---
layout: page
title:  "Eala"
permalink: /eala/
---

<section class="centered">

  <h3>Published Work</h3>

  <ul class="posts-list">
    {% for post in site.posts %}
    <li><strong><a class="post-link" href="{{ post.url }}">{{ post.title }} ({{ post.categories }})</a> </strong> by {{ post.author }}.</li>
    {% endfor %}
  </ul>


  <br />
  <br />

  {% include page_divider.html %}


<p>Eala publishes on a rolling basis and is currently online-only. We are <a href="/eala/submissions">open for submissions</a>.</p>

</section>
