---
layout: archive
title: "Publications and presentations"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

# Papers in prep
Farmer, J., Underwood, O., Pico, T., **Cleveland Stout, R.** PAPER. *In prep for Nature*.

# Published papers
**Cleveland Stout, R.**, Pico, T., Huybers, P., Austermann, J., Mitrovica, J. Leveraging preservation bias in Last Interglacial coral records to refine global ice volume estimates. XXX
