---
layout: article
title: Matematika
show_date: false
cover: /assets/images/subjects/math.jpg
---
Welcome to Mathematics Year 1!

On the left, you will find different chapters. We will provide practice material at the end of each chapter.

Below, you will be able to add comments to ask questions or answer fellow classmates' questions.

<div class="mt-2"></div>

{% assign temp_posts = site.posts | where_exp: "post", "post.group == 'Plugged-IN'" %}

{%- include article-list.html articles=temp_posts type='item' show_excerpt='true' show_info='true'-%}

<div class="mt-5"></div>
