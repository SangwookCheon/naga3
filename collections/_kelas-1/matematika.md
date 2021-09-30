---
layout: article
title: Matematika
show_date: false
cover: /assets/images/subjects/math.jpg
---

<div class="mt-2"></div>

{% assign temp_posts = site.posts | where_exp: "post", "post.group == 'kelas-1-matematika'" %}

{%- include article-list.html articles=temp_posts type='brief' show_info='true'-%}

<div class="mt-5"></div>
