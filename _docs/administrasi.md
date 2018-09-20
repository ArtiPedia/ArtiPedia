---
title: Kumpulan Administrasi Sekolah
description: Administrasi sekolah digunakan untuk mendukung dalam pengelolaan sekolah, pengelolaan pembelajaran bagi guru seperti RPP, Silabus, Program Tahunan, Program Semester, dll. 
permalink: /administrasi/
redirect_from: /docs/administrasi/
---

Berikut ini adalah kumpulan halaman dengan kategori administrasi
<ol class="arti">{% for post in site.categories.administrasi %}
<li class="{% if page.title == post.title %}current{% endif %}">
<a href="{{ post.url }}">{{ post.title }}</a>
</li>
{% endfor %}
</ol>
