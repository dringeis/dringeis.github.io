---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

### Review karma

| First-author papers accepted or published   |    Paper reviewed     | Paper karma                              |
| :-----------------------------------------: | :-------------------: | :--------------------------------------: |
|               2                             |           4           |    <span style="color:green"> 2 </span>    |

I've a neutral paper karma, contact me to review scientific papers (within my expertise).

----

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
