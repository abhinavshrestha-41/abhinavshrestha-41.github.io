---
layout: archive
title: "CV"
permalink: /cv/
author_profile: false
redirect_from:
  - /resume
---
{% include base_path %}
<body>
  <a href="/files/AbhinavShrestha_CV.pdf" download>Click here to download a pdf copy</a>
  <br>
  <hr>
  <iframe src="/files/AbhinavShrestha_CV.pdf#page=1&zoom=page-fit" width="100%" height="700px" marginwidth="0"> </iframe>
</body>

{% for post in site.CV %} 
  {% include archive-single.html %}
{% endfor %}
