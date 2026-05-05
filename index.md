---
layout: default
title: "Home"
---

```text
00000000  6e 75 6c 6c 6f 6e 65 40 6e 75 6c 6c 00 ff 13 37  |nullone@null...7|
00000010  de ad be ef 00 00 7f 45 4c 46 02 01 01 00 90 90  |.......ELF......|
```

## whoami

generic computer person

## about.txt

Collection of stuffs I wanted on the interwebs.

## posts

{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url | relative_url }}) — `{{ post.date | date: "%Y-%m-%d" }}`
{% endfor %}

## contact.txt


- GitHub: `https://github.com/nullone-special`
- Email: `nullone_special [at] protonmail[.]com`

