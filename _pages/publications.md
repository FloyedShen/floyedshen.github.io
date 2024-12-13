---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<div class="wordwrap">You can also find my articles on <a href="https://scholar.google.com/citations?user=Sv-WdBkAAAAJ&hl">my Google Scholar profile</a>.</div> Below are selected publications.

{% include base_path %}

<!-- New style rendering if publication categories are defined -->
{% if site.publication_category %}
{% for category in site.publication_category %}
{% assign title_shown = false %}
{% for post in site.publications reversed %}
{% if post.category != category[0] %}
{% continue %}
{% endif %}
{% unless title_shown %}
<h2>{{ category[1].title }}</h2>
<hr />
{% assign title_shown = true %}
{% endunless %}
{% include archive-single.html %}
{% endfor %}
{% endfor %}
{% else %}
{% for post in site.publications reversed %}
{% include archive-single.html %}
{% endfor %}
{% endif %}