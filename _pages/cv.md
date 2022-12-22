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
  <iframe src="/files/Shrestha_CV.pdf" width="100%" height="700px" marginwidth="0"> </iframe>
  <a href="/files/Shrestha_CV.pdf" download>Download CV (CLICK HERE)</a>
</body>

{% for post in site.CV %} 
  {% include archive-single.html %}
{% endfor %}
