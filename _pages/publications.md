---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

### Review karma

| First-author papers accepted or published   |    Paper reviewed divided by 2     | Paper karma                              |
| :-----------------------------------------: | :--------------------------------: | :--------------------------------------: |
|               2                             |                   2                |    <span style="color:green"> 0 </span>  |

I've a neutral paper karma, contact me to review scientific papers (within my expertise).

----

You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
