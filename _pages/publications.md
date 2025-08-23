---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

<!-- Academic Service Section -->
<div class="wordwrap">
  <strong>Academic Service:</strong> Reviewer for <em><a href="https://www.springer.com/journal/11053">Nuclear Science and Engineering</a></em>
</div>

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
