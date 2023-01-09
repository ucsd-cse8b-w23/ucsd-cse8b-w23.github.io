---
layout: with-sidebar
index: 6
name: Classes and Objects
released-on: "2023-01-23"
videos:
  - title: Creating Objects and Classes (through 22:00)
    url: https://drive.google.com/file/d/1Kn6rVGCTQf2OkZ5-maVpA-MXFd0LHxZ2
  - title: Point add() Method 1
    url: https://drive.google.com/file/d/1PV8W3eaBZbOab42mzne7Wts_kwEuz6ZU
  - title: Point add() Method 2
    url: https://drive.google.com/file/d/1yZX5wo3b-A5AxOwSIccQqsUR3VK0j26i
  - title: Math methods
    url: https://drive.google.com/file/d/1-5P1JWdzCCfGpwh1aW7jLYApipzJgmKc

worksheets:

---

## Problem Session 6 – Classes and Constructors

_{{ page.released-on }}_

## Pre-class Tasks

Readings to be completed **before** problem session.

- Stepik Chapter 5 [https://stepik.org/lesson/573908/step/1?unit=568498](https://stepik.org/lesson/573908/step/1?unit=568498)

Videos (to watch **before** problem session):

{% for video in page.videos %}
[{{ video.title }}]({{ video.url }}){:target="_blank"}

<iframe src="{{ video.url }}/preview" width="640" height="480" allow="autoplay"></iframe>
{% endfor %}

Handout:

<iframe src="https://drive.google.com/file/d/1un1uKkq6tHcGb-KEYW0pcm2Ldcb5hZR_/preview" width="640" height="480" allow="autoplay"></iframe>

## Completed Worksheets from Lecture

{% for worksheet in page.worksheets %}
<div class="worksheetBox">
{{ worksheet.title }}
<br>
<iframe src="{{ worksheet.url }}/preview" width="256" height="192" allow="autoplay"></iframe>
</div>
{% endfor %}