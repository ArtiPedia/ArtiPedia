---
title: Format Penulisan
permalink: /docs/format-penulisan/
---

## Header
Penulisan sub judul 

{% raw %}
```liquid
# Judul <h1> tag
## Sub Judul <h2> tag
### Sub Judul <h3> tag
#### Sub Judul <h4> tag
##### Sub Judul <h5> tag
###### This is an <h6> tag
```
{% endraw %}

Hasilnya
# Judul h1 
## Sub Judul h2 
### Sub Judul h3 
#### Sub Judul h4 
##### Sub Judul h5 
###### Sub Judul h6

## Bold
Menebalkan huruf terdapat dua cara
```
1. **Contoh**
2. __Contoh__.
```
Hasilnya
**Contoh**

## Italic
```
1. *Contoh*
2. _Contoh_.
```
Hasilnya
*Contoh*

## Blockquote
Untuk menambahkan <code>blockquote</code> tambahkan <code>></code> sebelum/pada awal paragraf
```
> Tes penulisan blockquote
```
Hasilnya
> Tes penulisan blockquote

{% raw %}
```liquid
{{ site.baseurl }}{% link _collection/name-of-document.md %}
{{ site.baseurl }}{% link _posts/2016-07-26-name-of-post.md %}
{{ site.baseurl }}{% link news/index.html %}
{{ site.baseurl }}{% link /assets/files/doc.pdf %}
```
{% endraw %}


 
