---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

{% if page.author and site.data.authors[page.author] %}
  {% assign author = site.data.authors[page.author] %}{% else %}{% assign author = site.author %}
{% endif %}

{% if true %}
  See also <a href="{{author.googlescholar}}">my Google Scholar profile</a>
  and <a href="{{author.dblp}}">my DBLP page</a>.
{% endif %}

{% for post in site.publications reversed %}
  {% include archive-single-publication.html %}
{% endfor %}
