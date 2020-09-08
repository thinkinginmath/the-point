---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

## Zoom 信息

[https://thepoint.zoom.us/j/95808449209](https://thepoint.zoom.us/j/95808449209).
會議密碼：100149

每週日聚會時間：
```
週日禱告 9:00AM-9:30AM
  主日學 9:30AM-10:15AM
主日敬拜 10:30AM-12:00PM
```

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
