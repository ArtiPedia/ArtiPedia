---
title: Kumpulan RPP
description: Halaman ini merupakan kumpulan Rencana Pelaksanaan Pembelajaran yang dimuat dalam blog ini dengan kategori RPP. Tambahkan RPP yang belum ada menurut anda.
permalink: /rpp/
redirect_from: /docs/rpp/
---

RPP merupakan salahsatu administrasi kelas yang harus dibuat oleh guru agar kegiatan pelaksanaan pembelajaran lebih terarah sehingga tujuan pembelajaran akan tercapai dengan maksimal, halaman ini berisi kumpulan RPP yang dipublikasikan di web ini. 
<ol class="arti">{% for post in site.categories.rpp %}
<li class="{% if page.title == post.title %}current{% endif %}">
<a href="{{ post.url }}">{{ post.title }}</a>
</li>
{% endfor %}
</ol>
