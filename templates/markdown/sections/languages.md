{% extends "section.md" %}

{% block body %}
<table class="table table-hover">
{% for item in items %}
<tr>
  <td class='col-md-2'><strong>{{ item.language }}</strong></td>
  <td>{{ item.level }}</td>
  <td>{{ item.comment }}</td>
</tr>
{% endfor %}
</table>
{% endblock body %}
