# Deneme

Yazı
* liste
* liste

1. sdgfsgs
2. sdgfsdgd

```deneme
a = a+1;
```
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
