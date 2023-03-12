---
layout: with-sidebar
index: 27
name: AUA and Goodbye!
released-on: "2023-03-17"
worksheets:

---

## Problem Session {{ page.index }} – {{ page.name }}

_{{ page.released-on }}_

Survey to be completed (again) by tonight (2 points)

- [CSE 8B - Experiences in CSE - Winter 2023 I](https://forms.gle/JQpXU6F8eMGs5sxh7)

Please submit your CAPEs for the course at [https://cape.ucsd.edu/](https://cape.ucsd.edu/), including evaluations for your TAs!

The theme of this lecture is “Ask Us (Almost) Anything!” Feel free to ask questions about the course, CSE, our experience, programming, and so on. This can be a mix of review and other topics you find helpful. 

## Handout

<iframe src="https://drive.google.com/file/d/136ff6Qk8LZDZk8GxfjzZqIwO_kRa2p8S/preview" width="640" height="480" allow="autoplay"></iframe>

## Completed Worksheets from Lecture

{% for worksheet in page.worksheets %}
<div class="worksheetBox">
{{ worksheet.title }}
<br>
<iframe src="{{ worksheet.url }}/preview" width="640" height="480" allow="autoplay"></iframe>
</div>
{% endfor %}