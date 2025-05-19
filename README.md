- Programmer 
- Somewhat of a Sysadmin 
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

### Quizzes

Solve these if you're taking those courses :)
- **[Social Media Analytics Quiz](https://linlyboi.github.io/quizzes/sma-quiz)**
- **[NLP Quizzes](https://linlyboi.github.io/quizzes/nlp)**
- **[Digital Broadcasting](https://linlyboi.github.io/quizzes/broadcasting-quiz)**
- **[Social Media Analytics Revision](https://linlyboi.github.io/quizzes/sma-revision)**
- **[Digital Forensics](https://linlyboi.github.io/quizzes/forensics)**
- **[Photography](https://linlyboi.github.io/quizzes/photography)**
<ul>
  {% for quiz in site.pages %}
    {% if quiz.identifier == 'quiz' %}
  <li>
    {{ quiz.title }}
  </li>
  {% endif %}
  {% endfor %}
</ul>
