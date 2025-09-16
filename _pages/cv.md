---
layout: default
title: "CV"
permalink: /cv/
author_profile: false
redirect_from:
  - /resume
---
{% include base_path %}

<style>
  /* Page specific styles */
  .page__content {
    max-width: 900px;  /* or 100% if you want full width */
    margin: 0 auto;
    padding: 1rem;
  }
</style>
<body>
  <a href="/files/AbhinavShrestha_CV.pdf" download>Click here to download a pdf copy</a>
  <br>
  <hr>
  <iframe src="/files/AbhinavShrestha_CV.pdf#page=1&zoom=100" width="100%" height="700px" marginwidth="0"> </iframe>
</body>

{% for post in site.CV %} 
  {% include archive-single.html %}
{% endfor %}
