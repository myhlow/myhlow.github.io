## Members

<br>
### Faculty

<ul>
  {% for faculty in site.faculty %}
    <li>
      <a href="{{ faculty.photo_url }}">{{ faculty.name }}</a>
    </li>
  {% endfor %}
</ul>

