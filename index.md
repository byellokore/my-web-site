---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
hero_darken: true
title: Seja bem-vindo! Conteúdo em Português.
hide_footer: true
---
<h1>Posts</h1>
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>


<section class="section">
<div class="columns ">
  <div class="column">
    I'm not writing in English at this moment because there is lack of content in Portuguese for Ruby/Ruby on Rails. I think it will help a lot if I only write in Portuguese. In the near future, I will post in both languages and maybe in French!. 
  </div>
</div>
</section>