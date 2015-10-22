---
layout: default
title: Eyeball Test
permalink: /posts/eyeball-test/
---

<img src='/content/banner/eyeball-test.png' />
<div style="width:100%;height:15px;border-bottom: 1px solid #FDBB30;"></div>

# Eyeball Test

<ul class="post-list">
 {% for post in site.categories.notes %}
   <li>
     <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>

     <h2>
       <a class="post-link" href="{{ post.url | prepend: site.baseurl | append: '/' }}">{{ post.title }}</a>
     </h2>
	  <p>written by {{ post.author }}</p>
   </li>
 {% endfor %}
</ul>