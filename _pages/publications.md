---
layout: archive
title: "Publication and Preprint"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<div class="publications-list">
{% for post in site.publications reversed %}
  <p>{{ post.citation | remove: '<p>' | remove: '</p>' }}</p>
{% endfor %}
</div>
