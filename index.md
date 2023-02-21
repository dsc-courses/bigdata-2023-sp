---
layout: home
title: 🏠 Home
nav_exclude: false
nav_order: 1
---

# {{ site.tagline }}

{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

<!-- for the old icon: >
 <!-- <img src='favicon.ico' style='vertical-align: text-top' width=37> -->

{{ site.staffersnobio }}

<!-- {: .success } -->

<!-- Welcome to CSE 255! 👋
Make sure to read the [Syllabus](syllabus) section.  -->

{% for module in site.modules %}
{{ module }}
{% endfor %}

<!-- <center>
<iframe src="10-80-enrollment.html" scrolling="no" style="border:none;" seamless="seamless" height="480" width="100%">
</center> -->
