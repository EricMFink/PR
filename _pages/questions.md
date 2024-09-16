---
layout: page
title: Questions
permalink: /questions/
---

<ul>
{% for question in site.questions %}
<li>
<a href="{{ site.url }}{{ site.baseurl }}{{ question.url }}">{{ question.title }}</a>
</li>
{% endfor %}
</ul>