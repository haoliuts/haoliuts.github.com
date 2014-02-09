---
layout: page
title: What color is your sky？
tagline:
---
{% include JB/setup %}
## About me
上海西南某高校毕业，外企小程序员一只～  
目前工作内容：开源编译器，LLVM  

***


## Blog list
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


