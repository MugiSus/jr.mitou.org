---
layout: post
title: "らくらく読み読み"
permalink: /projects/2017/rakuraku_yomiyomi
thumbnail: /assets/img/thumbnails/2017/tbu.png
description: "視力が低下したお年寄りから子どもまでが楽にニュース記事を読めるアプリ。文字の表示の工夫、読み進めた部分のマーキング、視線追跡などの機能を搭載。"
---

{% assign pj = site.data.projects | where_exp: "pj", "pj.id == 'rakuraku_yomiyomi'" | first %}

<img class='top-img lazyload' src='/assets/img/spinner.svg' alt='サムネイル画像' loading='lazy'
{% if pj.thumbnail == "tbu.png" %} data-src='https://img.youtube.com/vi/jQA4kApjr8s/hqdefault.jpg'
{% else %}                         data-src='/assets/img/thumbnails/2017/tbu.png'
{% endif %}                        style='margin-bottom: 10px;' />

視力が低下したお年寄りから子どもまでが楽にニュース記事を読めるアプリ。文字の表示の工夫、読み進めた部分のマーキング、視線追跡などの機能を搭載。

### クリエータ（採択年度：<a href='/projects/2017'>2017年度</a>）
<p>
{% for creator_id in pj.creator_ids %}
  {% include creator.html is_simple=true %}
{% endfor %}
</p>

### メンター
<p>{% include link-to-mentor.html id=pj.mentor_id %}</p>

## 発表動画
<div class="youtube">
  <iframe width="560" height="315" class="lazyload" data-src="https://www.youtube.com/embed/jQA4kApjr8s?rel=0" frameborder="0" allowfullscreen=""></iframe>
</div>
