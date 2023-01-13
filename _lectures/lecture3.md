---
layout: with-sidebar
index: 3
name: Methods
released-on: "2023-01-13"
videos:
  - title: Diagramming and Vocabulary Review
    url: https://drive.google.com/file/d/1lxNyu3kfqZ4wREkxrX8h7a2p_LpB1okR
  - title: Values and Evaluation
    url: https://drive.google.com/file/d/1Ts-T_hYkeFBgWTSQUieGFTlVYPz5M1sv
  - title: Talking About Expressions
    url: https://drive.google.com/file/d/1VUn3Z7vfMwIBWwbFocYLyLmj76Aya7vQ
  - title: Method Definitions
    url: https://drive.google.com/file/d/1g_gHQ3Bm8s4dPHvIIkrh9e7Bwl8ZBehw
  - title: Method Diagramming and Vocabulary
    url: https://drive.google.com/file/d/1m_72isftSttgHZ9Rj9PR1I4hPbzzAFyH

worksheets:
  - title: Lecture
    url: https://drive.google.com/file/d/1v26HhSSdwxjyolCQS_0Vnj5LJtgKV-pc
---

## Lecture 3 – Vocabulary and Methods

_{{ page.released-on }}_

## Pre-class Tasks

Readings to be completed **before** lecture.

- [Stepik 3.1-3.4](https://stepik.org/lesson/559662/step/1?unit=553722){:target="_blank"}

The university requires us to determine which students commence academic activity. Failure to certify academic activity, may result in students being billed for unearned financial aid.

To do this automatically, we are using a survey in Canvas that every student must fill out by the end of Friday of Week 2
to ensure that they are certified.
- [First Day Survey: Tell Me About Yourself #FinAid](https://canvas.ucsd.edu/courses/42489/quizzes/125584){:target="_blank"} 

Videos (to watch **before** lecture):

{% for video in page.videos %}
[{{ video.title }}]({{ video.url }}){:target="_blank"}

<iframe src="{{ video.url }}/preview" width="640" height="480" allow="autoplay"></iframe>
{% endfor %}

Handout (used during the session), [direct link](https://drive.google.com/file/d/1tYAjHJ390PPuaBSMFdIPL1N4_jt4P1Jn/preview){:target="_blank"}

<iframe src="https://drive.google.com/file/d/1tYAjHJ390PPuaBSMFdIPL1N4_jt4P1Jn/preview" width="640" height="480" allow="autoplay"></iframe>

## Completed Worksheets from Lecture

{% for worksheet in page.worksheets %}
<div class="worksheetBox">
{{ worksheet.title }}
<br>
<iframe src="{{ worksheet.url }}/preview" width="256" height="192" allow="autoplay"></iframe>
</div>
{% endfor %}
