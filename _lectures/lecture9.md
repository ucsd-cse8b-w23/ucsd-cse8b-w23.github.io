---
layout: with-sidebar
index: 9
name: Nested Data
released-on: "2023-01-30"
worksheets:
  - title: Lecture
    url: https://drive.google.com/file/d/1AY75vdoSqrjp72PzR0oGhlZUb8nvLEXo
---

## Problem Session {{ page.index }} – {{ page.name }}

_{{ page.released-on }}_

## Pre-class Tasks

Stepik reading (to complete before class):
- [Stepik 7](https://stepik.org/lesson/584041/step/10?unit=578810)

No pre-watch videos for this lecture.

If you want to watch ahead, the next topic will be from here, but we won't
discuss interfaces until the next class:

<iframe src="https://drive.google.com/file/d/1FsiNPr6N5yiFymHtwCdDHYHt03mWNw_Q/preview" width="640" height="480" allow="autoplay"></iframe>

Handout:

<iframe src="https://drive.google.com/file/d/1wvRKNATi2jIPVW0lpfgvZB6UGHW5r7QP/preview" width="640" height="480" allow="autoplay"></iframe>

## Completed Worksheets from Lecture

{% for worksheet in page.worksheets %}
<div class="worksheetBox">
{{ worksheet.title }}
<br>
<iframe src="{{ worksheet.url }}/preview" width="640" height="480" allow="autoplay"></iframe>
</div>
{% endfor %}