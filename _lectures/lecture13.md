---
layout: with-sidebar
index: 13
name: public static void main
released-on: "2023-02-08"
videos:
  - title: main
    url: https://drive.google.com/file/d/18RKvuJa1oYTdiloR7zH7AGBI9ucYCBQp
  - title: args
    url: https://drive.google.com/file/d/14Vtg9aJoa_E_34yIR1CLKDXn1KHIC-0e
worksheets:
  - title: Lecture
    url: https://drive.google.com/file/d/1KYSonOuMWTv2IBSdqVjlxZoffPE_pJAG
---

## Problem Session {{ page.index }} – {{ page.name }}

_{{ page.released-on }}_

## Pre-class Tasks

Stepik reading (same as previous reading, so no new reading):
- [Stepik 9](https://stepik.org/lesson/579631/step/1?unit=574281)

{% for video in page.videos %}
[{{ video.title }}]({{ video.url }}){:target="_blank"}

<iframe src="{{ video.url }}/preview" width="640" height="480" allow="autoplay"></iframe>
{% endfor %}

## Handout

<iframe src="https://drive.google.com/file/d/1Ea7X5MGyLsYqoFUF_HvXYNhWxlf_EiKX/preview" width="640" height="480" allow="autoplay"></iframe>

## Completed Worksheets from Lecture

{% for worksheet in page.worksheets %}
<div class="worksheetBox">
{{ worksheet.title }}
<br>
<iframe src="{{ worksheet.url }}/preview" width="640" height="480" allow="autoplay"></iframe>
</div>
{% endfor %}