---
layout: with-sidebar
index: 21
name: Generics
released-on: "2023-03-03"
videos:
    - title: "Two Similar Loops"
      url: https://drive.google.com/file/d/1RKq-CprnjmDDGPqius4tOZL6F4Xrvf-Q
    - title: "Generics"
      url: https://drive.google.com/file/d/1Gvhq3JsXXSxfjEVwjzHl_5jgQeuX5ixO
    - title: "Implementing with Generics"
      url: https://drive.google.com/file/d/1bXk5leiFDmvc8b5fnqaox0Xd1AdwXS1_
worksheets:
  - title: Lecture
    url: https://drive.google.com/file/d/1xLG_M6-l-GCOdX04jBALZGq28rMHmS9l
---

## Problem Session {{ page.index }} – {{ page.name }}

_{{ page.released-on }}_

## Pre-class Tasks

Stepik 12.1: [https://stepik.org/lesson/614368/step/1?unit=609810](https://stepik.org/lesson/614368/step/1?unit=609810)

Videos:

{% for video in page.videos %}
[{{ video.title }}]({{ video.url }}){:target="_blank"}
<iframe src="{{ video.url }}/preview" width="640" height="480" allow="autoplay"></iframe>
{% endfor %}

## Handout

<iframe src="https://drive.google.com/file/d/1nHyd6hhGSr2E894lp5nzF6Zv5m2XJf1Z/preview" width="640" height="480" allow="autoplay"></iframe>

## Completed Worksheets from Lecture

{% for worksheet in page.worksheets %}
<div class="worksheetBox">
{{ worksheet.title }}
<br>
<iframe src="{{ worksheet.url }}/preview" width="640" height="480" allow="autoplay"></iframe>
</div>
{% endfor %}