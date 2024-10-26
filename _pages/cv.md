---
layout: cv
permalink: /cv/
title: cv
nav: true
nav_order: 4
cv_pdf: CV_Oct_24.pdf
description: CV (updated on October 25, 2024).
---

{% if page.cv_pdf %}<div class="cv-pdf"><a href="{{ site.baseurl }}/assets/pdf/{{ page.cv_pdf }}" target="_blank">Click here to view my CV in a new tab</a></div>{% endif %}

<div class="cv-iframe-container">
  <iframe src="{{ site.baseurl }}/assets/pdf/{{ page.cv_pdf }}#toolbar=0" frameborder="0" width="100%" height="800px"> </iframe>
</div>
