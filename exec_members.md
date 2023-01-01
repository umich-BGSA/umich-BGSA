---
layout: default
---

# Executive Members

<div class="exec-container">
{% for i in site.data.execs %}
<div class="exec-card">
    <img class="exec-profile" src="/assets/execs/{{ i.photo }}" alt="{{ i.name }}" >
    <div class="exec-name"> {{ i.name }} </div>
    <div class="exec-position"> {{ i.position }} </div>
    <div class="exec-email">{{ i.email }}</div>
</div>
{% endfor %}
<div>
