---
layout: with-sidebar
index: 24
name: Class Hierarchy
released-on: "2023-03-10"
videos:
    - title: "Exceptions in Constructors"
      url: https://drive.google.com/file/d/18cK8aOJ5u2shclhOltpPwUoELer3vHgI
    - title: "Abstract Classes (31:00 to end)"
      url: https://drive.google.com/file/d/1p5wapPyh34kEMqNKxNZKH_RqSoFeV70m
    - title: "Abstract Classes 2 (First 2:00 - 20:00)"
      url: https://drive.google.com/file/d/1Xp7owWbOOTB4ubOQgiwyI-En6ubOiDzN
worksheets:

---

## Problem Session {{ page.index }} – {{ page.name }}

_{{ page.released-on }}_

## Pre-class Tasks

Stepik 12.2 (finish if you didn't for Wednesday): [https://stepik.org/lesson/578016/step/1?unit=572623](https://stepik.org/lesson/578016/step/1?unit=572623)

Videos:

{% for video in page.videos %}
[{{ video.title }}]({{ video.url }}){:target="_blank"}
<iframe src="{{ video.url }}/preview" width="640" height="480" allow="autoplay"></iframe>
{% endfor %}

## Handout

<iframe src="https://drive.google.com/file/d/1wI8nLx79JLqorJFjHy79IGDm_KbprdHp/preview" width="640" height="480" allow="autoplay"></iframe>

## Completed Worksheets from Lecture

{% for worksheet in page.worksheets %}
<div class="worksheetBox">
{{ worksheet.title }}
<br>
<iframe src="{{ worksheet.url }}/preview" width="256" height="192" allow="autoplay"></iframe>
</div>
{% endfor %}