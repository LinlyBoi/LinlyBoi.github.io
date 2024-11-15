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
  {% assign quizes = site.pages | where_exp: "item" , "item.path contains 'quizes'"%}
  {% for item in quizes %}
  <li>
    <a href="{{ item.url }}">{{ item.title }}</a>
  </li>
  {% endfor %}
</ul>
