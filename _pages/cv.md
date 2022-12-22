---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
<body>
  <a href="/files/Shrestha_CV.pdf" download>Click here to download a pdf copy</a>
  <iframe src="/files/Shrestha_CV.pdf" width="100%" height="700px" marginwidth="0"> </iframe>
</body>

{% for post in site.CV %} 
  {% include archive-single.html %}
{% endfor %}
