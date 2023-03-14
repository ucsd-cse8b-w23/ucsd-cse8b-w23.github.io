---
layout: with-sidebar
index: 25
name: Equality, Overrides
released-on: "2023-03-13"
videos:
    - title: "Equals Ourselves"
      url: https://drive.google.com/file/d/1yq4xTudhikFAVH9gLRs_8Xe8wcLLmj4V
    - title: "instanceof"
      url: https://drive.google.com/file/d/1sw2rDZ9Qb-tK6KI2nCY_R7w9iypXH_RZ
    - title: "Casting"
      url: https://drive.google.com/file/d/1XFuMKAMREdoFzSBQ7HXwPtklvdwoC0TV
    - title: "toString()"
      url: https://drive.google.com/file/d/1yeM6VHMe6mLeIV_dpjx0yWG6XZ7QjlPo
worksheets:
  - title: Lecture
    url: https://drive.google.com/file/d/150AIO32kWUzgOFhv1ciYOydOuxCyYBSs
---

## Problem Session {{ page.index }} – {{ page.name }}

_{{ page.released-on }}_

## Pre-class Tasks

[Stepik 13](https://stepik.org/lesson/575460/step/1?unit=570041) (Abstract Classes)

Survey to be completed (again) by Friday (2 points)

- [CSE 8B - Experiences in CSE - Winter 2023 I](https://forms.gle/JQpXU6F8eMGs5sxh7)

(It's OK to watch these videos after class in this particular case, too, the class
introduces many of these topics)

Videos:

{% for video in page.videos %}
[{{ video.title }}]({{ video.url }}){:target="_blank"}
<iframe src="{{ video.url }}/preview" width="640" height="480" allow="autoplay"></iframe>
{% endfor %}

Code from lecture:

<script src="https://emgithub.com/embed.js?target=https%3A%2F%2Fgithub.com%2Fucsd-cse11-f21%2Fucsd-cse11-f21.github.io%2Fblob%2Fmain%2F_lectures%2Flecture26%2FPair.java&style=github&showBorder=on&showLineNumbers=on&showFileMeta=on&showCopy=on"></script>

Handout: 

<iframe src="https://drive.google.com/file/d/1oPmbMA2A-uXGXEQoGqZM5GARO6XvQJYf/preview" width="640" height="480" allow="autoplay"></iframe>

## Completed Worksheets from Lecture

{% for worksheet in page.worksheets %}
<div class="worksheetBox">
{{ worksheet.title }}
<br>
<iframe src="{{ worksheet.url }}/preview" width="640" height="480" allow="autoplay"></iframe>
</div>
{% endfor %}
