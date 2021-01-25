---
title : Discursos profissionais
layout: page
---

<table width="100%">
  <thead>
    <tr>
      <td>Autores</td><td>Título</td>
    </tr>
  </thead><tbody>
  {%- for paper in site.discurso %}
    <tr>
      <td>{{ paper.author }}</td>
      <td><a href="{{ paper.url }}">{{ paper.title }}</a></td>
    </tr>
  {% endfor -%}
  </tbody>
</table>