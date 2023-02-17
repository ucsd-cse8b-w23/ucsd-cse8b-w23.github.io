---
layout: with-sidebar
index: 19
name: File I/O, Exceptions
released-on: "2023-02-27"
videos:
  - title: Exceptions in Max
    url: https://drive.google.com/file/d/1TSkL7d1F2ooWNaOWEWCRtRnJ9nLVKyC6
  - title: File I/O Exception
    url: https://drive.google.com/file/d/1ZH88H8jrPK_W1CFr_U4WnvqJiRAoM6uT
  - title: File Processing Example
    url: https://drive.google.com/file/d/1obg1ktjlwbZJF3Sc4lfPxeKtmweqdSvF
  - title: Constructor Exceptions
    url: https://drive.google.com/file/d/18cK8aOJ5u2shclhOltpPwUoELer3vHgI
worksheets:

---

## Problem Session {{ page.index }} – {{ page.name }}

_{{ page.released-on }}_

## Pre-class Tasks

No Stepik chapter.

Videos:

{% for video in page.videos %}
[{{ video.title }}]({{ video.url }}){:target="_blank"}
<iframe src="{{ video.url }}/preview" width="640" height="480" allow="autoplay"></iframe>
{% endfor %}

## Handout

<iframe src="https://drive.google.com/file/d/1aDk4ldtEKIy29Q5hlei0YXzviDQvrSI5/preview" width="640" height="480" allow="autoplay"></iframe>

## Completed Worksheets from Lecture

{% for worksheet in page.worksheets %}
<div class="worksheetBox">
{{ worksheet.title }}
<br>
<iframe src="{{ worksheet.url }}/preview" width="256" height="192" allow="autoplay"></iframe>
</div>
{% endfor %}