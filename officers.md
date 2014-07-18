---
layout: page
title: Officers
permalink: /officers/
---

{% for officer in site.data.officers %}
<h3>{{ officer.title }}</h3>
<hr>
<div>{{ officer.name }}</div>
<div>{{ officer.email }}</div>
{% endfor %}
