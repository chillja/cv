{% extends "section.md" %}

{% block body %}
<table class="table table-hover">
{% for i in items %}
<tr>
  <td class='col-md-1'>{{ i.semester }}</td>
  <td><strong>{{ i.name }}</strong>{% if i.short %} ({{ i.short }}){% endif %}, {{ i.position }}</td>
</tr>
{% endfor %}
</table>
{% endblock body %}
