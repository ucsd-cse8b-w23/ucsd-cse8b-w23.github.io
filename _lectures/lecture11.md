---
layout: with-sidebar
index: 11
name: Interfaces and Recursion
released-on: "2023-02-03"
videos:
  - title: Interfaces (watch 30:00 to the end)
    url: https://drive.google.com/file/d/1FsiNPr6N5yiFymHtwCdDHYHt03mWNw_Q
worksheets:

---

## Problem Session {{ page.index }} – {{ page.name }}

_{{ page.released-on }}_

## Pre-class Tasks

Stepik reading:
- [Stepik 8.4-8.5](https://stepik.org/lesson/574433/step/1?unit=569019)

{% for video in page.videos %}
[{{ video.title }}]({{ video.url }}){:target="_blank"}

<iframe src="{{ video.url }}/preview" width="640" height="480" allow="autoplay"></iframe>
{% endfor %}

## Handout

(Yes, same as last lecture 🙂)

<iframe src="https://drive.google.com/file/d/1-zmTcKTnnjQ_BUlKNweC77BxgVBCecgn/preview" width="640" height="480" allow="autoplay"></iframe>

## Completed Worksheets from Lecture

{% for worksheet in page.worksheets %}
<div class="worksheetBox">
{{ worksheet.title }}
<br>
<iframe src="{{ worksheet.url }}/preview" width="640" height="480" allow="autoplay"></iframe>
</div>
{% endfor %}
