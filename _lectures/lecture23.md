---
layout: with-sidebar
index: 23
name: (Array)Lists
released-on: "2023-03-08"
videos:
    - title: "ArrayList"
      url: https://drive.google.com/file/d/1pdWAmNbX__aKAWBlZ6xyRujHeSJNPDgB
    - title: "LongStrings"
      url: https://drive.google.com/file/d/1_l1tZYs27wzgopZjnOv9txXGJOaug4JH
    - title: "ArrayLists – Overloading"
      url: https://drive.google.com/file/d/1hOvnt1rBitXqE91kS7xSrTrSZVNaX9dZ
worksheets:

---

## Problem Session {{ page.index }} – {{ page.name }}

_{{ page.released-on }}_

## Pre-class Tasks

Stepik 12.2: [https://stepik.org/lesson/578016/step/1?unit=572623](https://stepik.org/lesson/578016/step/1?unit=572623)

Videos:

{% for video in page.videos %}
[{{ video.title }}]({{ video.url }}){:target="_blank"}
<iframe src="{{ video.url }}/preview" width="640" height="480" allow="autoplay"></iframe>
{% endfor %}

## Handout

<iframe src="https://drive.google.com/file/d/1n9Si7OEv5yt7SwwsbjmAp3pmQf3csfFk/preview" width="640" height="480" allow="autoplay"></iframe>

## Completed Worksheets from Lecture

{% for worksheet in page.worksheets %}
<div class="worksheetBox">
{{ worksheet.title }}
<br>
<iframe src="{{ worksheet.url }}/preview" width="256" height="192" allow="autoplay"></iframe>
</div>
{% endfor %}