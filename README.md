- Programmer 
- Aspiring Sysadmin 
- CS Student
- Linux enthusiast 


## Boring Stuff  

- **[About (Linly) me!](https://linlyboi.github.io/about)**



### News 

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

### Quizes

Solve these if you're taking those courses :)
<ul>
  {% for quiz in site.pages %}
    {% if quiz.identifier == 'quiz' %}
  <li>
    {{ quiz.title }}
  </li>
    {% endif %}
  {% endfor %}
</ul>
