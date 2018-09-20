---
title: Kumpulan Berita Seputar Pendidikan
description: Halaman ini berisi kumpulan berita terupdate tentang Pendidikan, CPNS, ataupun lainnya yang sangat berguna bagi para pembaca.
permalink: /berita/
redirect_from: /docs/berita/
---

Halaman ini berisi kumpulan berita terupdate tentang Pendidikan, CPNS, ataupun lainnya yang sangat berguna bagi para pembaca.
<ol class="arti">{% for post in site.categories.berita %}
<li class="{% if page.title == post.title %}current{% endif %}">
<a href="{{ post.url }}">{{ post.title }}</a>
</li>
{% endfor %}
</ol>
