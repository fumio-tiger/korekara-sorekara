# ようこそ
GitHub Pages + Jekyll テーマのブログです。

- Markdown で書けます
- 自動でテーマが適用されます

## 最新記事

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <small>{{ post.date | date: "%Y-%m-%d" }}</small>
    </li>
  {% endfor %}
</ul>