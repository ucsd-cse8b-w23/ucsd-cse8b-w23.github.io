---
layout: with-sidebar
index: 12
name: Arrays
released-on: "2023-02-06"
videos:
  - title: Arrays
    url: https://drive.google.com/file/d/1TglDg1vHTC1ibjO4WJR8SJJSfvpMp9fC
  - title: Arrays, Indexing
    url: https://drive.google.com/file/d/1WkQ5PoQxwNFVio_tp9RD7y-h188zGKoF
  - title: Arrays, Methods
    url: https://drive.google.com/file/d/1PzrWhXBRerq0oTeVhlnuNc0vNJ6xQW9k
  - title: Arrays, Memory
    url: https://drive.google.com/file/d/14QiAfHlccvCZTVsU3MuBvLoFkSU-_UAo
worksheets:
  - title: Lecture
    url: https://drive.google.com/file/d/1JFlLHIiu4fHU5u5h-pYJPvdUo_koFTSO
---

## Problem Session {{ page.index }} – {{ page.name }}

_{{ page.released-on }}_

## Pre-class Tasks

Stepik reading:
- [Stepik 9](https://stepik.org/lesson/579631/step/1?unit=574281)

{% for video in page.videos %}
[{{ video.title }}]({{ video.url }}){:target="_blank"}

<iframe src="{{ video.url }}/preview" width="640" height="480" allow="autoplay"></iframe>
{% endfor %}

## Handout

<iframe src="https://drive.google.com/file/d/102yRmOqGB1uP-8zTqbUCR8szQbE_NP1v/preview" width="640" height="480" allow="autoplay"></iframe>

## Completed Worksheets from Lecture

{% for worksheet in page.worksheets %}
<div class="worksheetBox">
{{ worksheet.title }}
<br>
<iframe src="{{ worksheet.url }}/preview" width="640" height="480" allow="autoplay"></iframe>
</div>
{% endfor %}