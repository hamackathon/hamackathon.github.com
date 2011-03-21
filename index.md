---
layout: default
title: "浜松ハッカソン: Hamackathon"
---

浜松ハッカソン(通称: ハマッカソン)は、静岡県浜松市で定期的に開催しているソフトウェア開発者やWeb制作者の交流イベントです。

# お知らせ
<ul class="posts">
{% for post in site.posts limit:5 %}
<li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
