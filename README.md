# Academic Works

## Theses

<ul>
  {% for thesis in site.theses %}
    <li>
      <a href="{{ thesis.url }}">{{ thesis.title }}</a> ({{ thesis.type}}, {{ thesis.date | date: "%Y" }})
    </li>
  {% endfor %}
</ul>

## Articles

<ul>
  {% for article in site.articles %}
    <li>
      <a href="{{ article.url }}">{{ article.title }}</a> ({{article.status}})
    </li>
  {% endfor %}
</ul>

## Other Projects

- [LaTeX templates for various mathematical document types](https://github.com/flgrubm/latex-templates)
