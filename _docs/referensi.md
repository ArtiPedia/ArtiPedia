---
title: Kumpulan Referensi
description: Halaman ini merupakan kumpulan pembahasan/artikel yang dimuat dalam blog ini dengan kategori Referensi. Tambahkan referensi yang belum ada menurut anda.
permalink: /referensi/
redirect_from: /docs/referensi/
---

Halaman ini merupakan kumpulan pembahasan/artikel yang dimuat dalam blog ini dengan kategori Referensi.
<ol class="arti">{% for post in site.categories.referensi %}
<li class="{% if page.title == post.title %}current{% endif %}">
<a href="{{ post.url }}">{{ post.title }}</a>
</li>
{% endfor %}
</ol>
