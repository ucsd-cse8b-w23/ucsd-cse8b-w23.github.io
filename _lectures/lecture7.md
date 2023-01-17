---
layout: with-sidebar
index: 7
name: Memory and Tracing
released-on: "2023-01-25"
videos:
  - title: Creating Objects and Classes (22:00 - 38:00)
    url: https://drive.google.com/file/d/1Kn6rVGCTQf2OkZ5-maVpA-MXFd0LHxZ2
  - title: Line Class
    url: https://drive.google.com/file/d/1bFzLGW75Y68hAEVe3ERDvdQf7jHJ0Kin
  - title: Calc-Y
    url: https://drive.google.com/file/d/1WSf8sB8OZOz8Y4O8x7l4qKLP4McYIqo7

worksheets:

---

## Problem Session {{ page.index }} – {{ page.name }}

_{{ page.released-on }}_

## Pre-class Tasks

Readings to be completed **before** problem session.

- No Stepik readings for this lecture

Videos (to watch **before** problem session):

{% for video in page.videos %}
[{{ video.title }}]({{ video.url }}){:target="_blank"}

<iframe src="{{ video.url }}/preview" width="640" height="480" allow="autoplay"></iframe>
{% endfor %}

Handout:

<iframe src="https://drive.google.com/file/d/1wvTxXV-nLz0lDFDZx5qnJH9vzj9MUzQx/preview" width="640" height="480" allow="autoplay"></iframe>

## Completed Worksheets from Lecture

{% for worksheet in page.worksheets %}
<div class="worksheetBox">
{{ worksheet.title }}
<br>
<iframe src="{{ worksheet.url }}/preview" width="640" height="480" allow="autoplay"></iframe>
</div>
{% endfor %}