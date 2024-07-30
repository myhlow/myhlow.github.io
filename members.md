## Members

<ul>
  {% for faculty in site.faculty %}
    <li>
      <a href="{{ faculty.url }}">{{ faculty.title }}</a>
    </li>
  {% endfor %}
</ul>
