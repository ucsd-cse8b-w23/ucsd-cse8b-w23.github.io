---
layout: with-sidebar
index: 2
name: Classes and Fields
released-on: "2023-01-11"
videos:
  - title: Introduction to Running Programs
    url: https://drive.google.com/file/d/1PK-B_xRonGca_x8fLDRl1OPZqSceHk5x
  - title: Syntax Errors
    url: https://drive.google.com/file/d/1DHJz-KEbARV4aUio7e2LDsDtjm7qB_YO
  - title: Arithmetic
    url: https://drive.google.com/file/d/1lB4Mf9FEtw49V8phNGN1OQJPafkTtkt0
  - title: Field Access
    url: https://drive.google.com/file/d/1NWioGWa0pA86IlP-Ry7DMDneNdc64xXX

worksheets:
  - title: Lecture
    url: https://drive.google.com/file/d/1usYwejzkP9fl8oqABofkJByaOJ2oAYGy
---

## Lecture 2 – Classes and Fields

_{{ page.released-on }}_

## Pre-class Tasks

Readings to be completed **before** lecture.

You will need to make an account on Stepik to have your work saved.
- [Stepik 1.1-1.3](https://stepik.org/lesson/559661/step/1?unit=553721){:target="_blank"}
- [Stepik 2.1-2.3](https://stepik.org/lesson/571216/step/1?unit=565754){:target="_blank"}

To ensure you get credit for the Stepik exercises, you must fill out this [form](https://forms.gle/auRT3tLeJkmF91Lb9){:target="_blank"}
by Friday of Week 2. Starting in Week 3, we will strive to post Stepik grades to Canvas every week.

The university requires us to determine which students commence academic activity. Failure to certify academic activity, may result in students being billed for unearned financial aid.

To do this automatically, we are using a survey in Canvas that every student must fill out by the end of Friday of Week 2
to ensure that they are certified.
- [First Day Survey: Tell Me About Yourself #FinAid](https://canvas.ucsd.edu/courses/42489/quizzes/125584){:target="_blank"} 

Videos (to watch **before** lecture):

{% for video in page.videos %}
[{{ video.title }}]({{ video.url }}){:target="_blank"}

<iframe src="{{ video.url }}/preview" width="640" height="480" allow="autoplay"></iframe>
{% endfor %}

Handout (used during the session), [direct link](https://drive.google.com/file/d/1tYgRg4gGFcUE_BD5HXJBbh86ccCYs6pS/preview){:target="_blank"}

<iframe src="https://drive.google.com/file/d/1tYgRg4gGFcUE_BD5HXJBbh86ccCYs6pS/preview" width="640" height="480" allow="autoplay"></iframe>

## Completed Worksheets from Lecture

{% for worksheet in page.worksheets %}
<div class="worksheetBox">
{{ worksheet.title }}
<br>
<iframe src="{{ worksheet.url }}/preview" width="640" height="480" allow="autoplay"></iframe>
</div>
{% endfor %}
