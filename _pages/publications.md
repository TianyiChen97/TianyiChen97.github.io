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
{% for pub in site.data.publications %}
  <p>{{ pub.citation }}</p>
{% endfor %}
</div>
