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
{% for page in site.pages %}
  <a href="{{ page.url }}">{{ page.title }}</a>
  <!-- <p>{{ page.content }}</p> -->
{% endfor %}
