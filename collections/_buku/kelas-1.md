---
layout: article
title: Kelas 1
show_date: false
cover: /assets/images/subjects/math.jpg
---

## Matematika

<div class="mt-2"></div>

{% assign temp_posts = site.posts | where_exp: "post", "post.group == 'kelas-1-buku'" %}

{%- include article-list.html articles=temp_posts type='brief' show_excerpt='true' show_info='true'-%}

<div class="mt-5"></div>

## IPA

{% assign temp_posts = site.posts | where_exp: "post", "post.group == 'kelas-1-buku'" %}

{%- include article-list.html articles=temp_posts type='brief' show_excerpt='true' show_info='true'-%}

<div class="mt-5"></div>
