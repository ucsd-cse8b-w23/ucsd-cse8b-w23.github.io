---
layout: with-sidebar
index: 22
name: More Generics
released-on: "2023-03-06"
videos:
    - title: "Generic Definitions (Pair)"
      url: https://drive.google.com/file/d/1kvdNWRXNwe0oldTiPZa6IvUL56XPUo0X
    - title: "Wrapper Classes (Integer/Double/Boolean)"
      url: https://drive.google.com/file/d/1fxNkBh_BBr9uLfRtpU8X2B2FT9dq9Lne
worksheets:

---

## Problem Session {{ page.index }} – {{ page.name }}

_{{ page.released-on }}_

## Pre-class Tasks

No new reading.

Videos:

{% for video in page.videos %}
[{{ video.title }}]({{ video.url }}){:target="_blank"}
<iframe src="{{ video.url }}/preview" width="640" height="480" allow="autoplay"></iframe>
{% endfor %}

## Handout

<iframe src="https://drive.google.com/file/d/1nID8ZblgR1wrfQo-C0YtiodMiu5zD7qZ/preview" width="640" height="480" allow="autoplay"></iframe>

## Completed Worksheets from Lecture

{% for worksheet in page.worksheets %}
<div class="worksheetBox">
{{ worksheet.title }}
<br>
<iframe src="{{ worksheet.url }}/preview" width="256" height="192" allow="autoplay"></iframe>
</div>
{% endfor %}