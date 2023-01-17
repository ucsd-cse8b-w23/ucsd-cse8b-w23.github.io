---
layout: with-sidebar
index: 5
name: Booleans and If
released-on: "2023-01-20"
videos:
  - title: More on String Methods
    url: https://drive.google.com/file/d/1rYWNaFbrW5W-ITueTlzaPzW8k-CkTuWX
  - title: A Design Recipe Example
    url: https://drive.google.com/file/d/1WgbC_LPGfsRbj-ybdoYYg8SHl8W5Ryvd
  - title: Booleans
    url: https://drive.google.com/file/d/1LHxrTqZfszFmsF6xDTCD8SbAO2iemxY5
  - title: If (watch from 26:00 to 37:30)
    url: https://drive.google.com/file/d/1Akg2I_XKXuyOImRrVD6phPk-x-YBfcL8

worksheets:

---

## Problem Session 5 – Booleans and If

_{{ page.released-on }}_

## Pre-class Tasks

Readings to be completed **before** problem session.

- Stepik Chapter 4 [https://stepik.org/lesson/568133/step/1?unit=562510](https://stepik.org/lesson/568133/step/1?unit=562510)

Survey to be completed by Friday (2 points)

- [CSE 8B - Experiences in CSE - Winter 2023 I](https://forms.gle/JQpXU6F8eMGs5sxh7)

The university requires us to determine which students commence academic activity. Failure to certify academic activity, may result in students being billed for unearned financial aid.

To do this automatically, we are using a survey in Canvas that every student must fill out by the end of Friday of Week 2
to ensure that they are certified.
- [First Day Survey: Tell Me About Yourself #FinAid](https://canvas.ucsd.edu/courses/42489/quizzes/125584){:target="_blank"} 

Videos (to watch **before** problem session):

{% for video in page.videos %}
[{{ video.title }}]({{ video.url }}){:target="_blank"}

<iframe src="{{ video.url }}/preview" width="640" height="480" allow="autoplay"></iframe>
{% endfor %}

Handout

<iframe src="https://drive.google.com/file/d/1umlQ8PmNJBoov2DUEoI_RBLcEE-cQRjX/preview" width="640" height="480" allow="autoplay"></iframe>

## Completed Worksheets from Lecture

{% for worksheet in page.worksheets %}
<div class="worksheetBox">
{{ worksheet.title }}
<br>
<iframe src="{{ worksheet.url }}/preview" width="640" height="480" allow="autoplay"></iframe>
</div>
{% endfor %}