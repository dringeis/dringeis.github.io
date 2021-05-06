---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

### Publication and review count

| Paper Accepted or published   | Paper reviewed     | Paper debt                               |
| :---------------------------: | :----------------: | :--------------------------------------: |
|               2               |         0          |   <span style="color:red"> -2 </span>    |

I'm in paper debt, contact me for some review (within my expertise).

----

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
