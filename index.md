---
layout: default
title: "Home"
---

<pre>
00000000  6e 75 6c 6c 6f 6e 65 40 6e 75 6c 6c 00 ff 13 37  |nullone@null...7|
00000010  de ad be ef 00 00 7f 45 4c 46 02 01 01 00 90 90  |.......ELF......|
00000020  90 90 eb 1e 5b 31 c0 88 43 07 89 5b 08 89 43 0c  |....[1..C..[..C.|
00000030  b0 0b 8d 4b 08 8d 53 0c cd 80 e8 dd ff ff ff 2f  |...K..S......../|
00000040  62 69 6e 2f 73 68 58 00 00 00 00 00 00 00 00 00  |bin/shX.........|

<span class="prompt-user">nullone@null</span>:~$ whoami
generic computer person

<span class="prompt-user">nullone@null</span>:~$ cat about.txt
Collection of stuffs I wanted on the interwebs.

<span class="prompt-user">nullone@null</span>:~$ ls -lt /recent_posts
{% for post in site.posts limit:5 %}
-rw-r--r-- 1 nullone null {{ post.date | date: "%Y-%m-%d" }} {{ post.title }}
{% endfor %}

<span class="prompt-user">nullone@null</span>:~$ cat /posts/posts.links
{% for post in site.posts limit:5 %}
[{{ post.date | date: "%Y-%m-%d" }}] <a href="{{ post.url | relative_url }}">./{{ post.title | slugify }}/</a>
{% if post.tags %}tags: {% for tag in post.tags %}#{{ tag }} {% endfor %}{% endif %}

{% endfor %}

<span class="prompt-user">nullone@null</span>:~$ cat contact.txt
Email: nullone_special [at] protonmail[.]com
Github: https://github.com/nullone-special
</pre>
