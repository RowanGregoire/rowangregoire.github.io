---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<!-- Most of these publications may also be found on my <u><a href="https://scholar.google.com/citations?user=e_X_FwUAAAAJ">google scholar profile</a>.</u> -->

---
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<!-- ***

# Conference Presentations
{% for post in site.conferences reversed %}
  {% include archive-single.html %}
{% endfor %} -->
