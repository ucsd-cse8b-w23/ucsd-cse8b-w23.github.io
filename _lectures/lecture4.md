---
layout: with-sidebar
index: 4
name: String Methods
released-on: "2023-01-18"
videos:
  - title: Strings
    url: https://drive.google.com/file/d/1VFHfgw_tP8snhfDoEhns5ORbJz6UFeDw
  - title: String Concatenation
    url: https://drive.google.com/file/d/14bS8OZyY0oPYFlLCnFHZ6Vz5xAI6jzE8    
  - title: Strings and Numbers
    url: https://drive.google.com/file/d/1NBZa_qDiGO9V6cwWZddtBpNTQzF348oL
  - title: Method Evaluation
    url: https://drive.google.com/file/d/1WScX4N4gFNAlLoHdXwoVurQacUB2X2JF
  - title: String Methods
    url: https://drive.google.com/file/d/1WnSDBSOGSXnsvAvgdYduFYzuS9RTIscK

worksheets:

---

## Problem Session 4 – Strings and More Methods 

_{{ page.released-on }}_

## Pre-class Tasks

Readings to be completed **before** problem session.

- No Stepik readings for this lecture

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

<iframe src="https://drive.google.com/file/d/1tzRz20I_WkfdsbD1YTWOSRNDDMQclTEd/preview" width="640" height="480" allow="autoplay"></iframe>

## Completed Worksheets from Lecture

{% for worksheet in page.worksheets %}
<div class="worksheetBox">
{{ worksheet.title }}
<br>
<iframe src="{{ worksheet.url }}/preview" width="256" height="192" allow="autoplay"></iframe>
</div>
{% endfor %}
