---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if true %}
  See also <a href="{{author.googlescholar}}">my Google Scholar profile</a>
  and <a href="{{author.dblp}}">my DBLP page</a>.
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single-publication.html %}
{% endfor %}
