---
layout: post
title: "Example Post Title"
date: 2026-05-05
tags: [malware, reverse-engineering, notes]
---

<pre>
<span class="prompt-user">nullone@null</span>:~/posts$ cat example-post.txt

title: Example Post Title
date:  2026-05-05
tags:  malware reverse-engineering notes

<span class="prompt-user">nullone@null</span>:~/posts$ cat overview.txt
Brief summary of what this post is about.

<span class="prompt-user">nullone@null</span>:~/posts$ cat context.txt
What system, challenge, sample, lab, or topic you are looking at.

<span class="prompt-user">nullone@null</span>:~/lab$ file sample.bin
sample.bin: ELF 64-bit LSB executable, x86-64

<span class="prompt-user">nullone@null</span>:~/lab$ strings sample.bin | head
example_string_1
example_string_2
example_string_3

<span class="prompt-user">nullone@null</span>:~/posts$ cat findings.txt
[01] Finding one
[02] Finding two
[03] Finding three

<span class="prompt-user">nullone@null</span>:~/posts$ cat takeaways.txt
What you learned, what was interesting, and what you would try next.

<span class="prompt-user">nullone@null</span>:~/posts$ cat references.txt
[01] https://example.com
[02] https://example.com/research
</pre>
