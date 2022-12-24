---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---
<head>
<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-1S4DNGHWWE"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-1S4DNGHWWE');
</script>
</head>

{% include base_path %}
<body>
  <a href="/files/Shrestha_CV.pdf" download>Click here to download a pdf copy</a>
  <br>
  <hr>
  <iframe src="/files/Shrestha_CV.pdf" width="100%" height="700px" marginwidth="0"> </iframe>
</body>

{% for post in site.CV %} 
  {% include archive-single.html %}
{% endfor %}
