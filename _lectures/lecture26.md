---
layout: with-sidebar
index: 26
name: Modifiers, Invariants
released-on: "2023-03-15"
videos:
    - title: "Access Modifiers"
      url: https://drive.google.com/file/d/1j8xtQfJtdHfBDp_4eINFE7xYg2IUEs7g
    - title: "Default Package"
      url: https://drive.google.com/file/d/1jIgflYWbjJdfdRz5Kh0LTLBSP54nnlbM
    - title: "Protected"
      url: https://drive.google.com/file/d/1-2lleGWYeeXkiTaRmWbTtOeM3lZ7uHSP
worksheets:

---

## Problem Session {{ page.index }} – {{ page.name }}

_{{ page.released-on }}_

## Pre-class Tasks

[Stepik 13](https://stepik.org/lesson/575460/step/1?unit=570041) (Abstract Classes)

Survey to be completed (again) by Friday (2 points)

- [CSE 8B - Experiences in CSE - Winter 2023 I](https://forms.gle/JQpXU6F8eMGs5sxh7)

Videos:

{% for video in page.videos %}
[{{ video.title }}]({{ video.url }}){:target="_blank"}
<iframe src="{{ video.url }}/preview" width="640" height="480" allow="autoplay"></iframe>
{% endfor %}

## Handout

<iframe src="https://drive.google.com/file/d/1oNtdzXEPiDKDlx5ROL-KouiWpPHLbz2g/preview" width="640" height="480" allow="autoplay"></iframe>

## Completed Worksheets from Lecture

{% for worksheet in page.worksheets %}
<div class="worksheetBox">
{{ worksheet.title }}
<br>
<iframe src="{{ worksheet.url }}/preview" width="640" height="480" allow="autoplay"></iframe>
</div>
{% endfor %}