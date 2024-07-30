## Members

<ul>
  {% for fac in site.faculty %}
    <li>
      <a href="{{ fac.url }}">{{ fac.title }}</a>
    </li>
  {% endfor %}
</ul>
