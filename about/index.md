---
layout: page
title: "横山研究室について"
date: 2018-04-01
excerpt: "横山研究室は2018年4月に発足した東京都立大学システムデザイン学部情報科学科に属するデータベースやデータ工学に関する研究室です。"
about: true
comments: false
---

## ご挨拶

東京都立大学システムデザイン学部情報科学科に属するデータベースやデータ工学に関する研究室です。横山研では人と人とのコミュニケーションにより発せられるビッグデータの分析を主軸に以下の２つの課題の研究を勧めています。

* Twitter等のソーシャルビッグデータを用いた可視化・分析
* 5Gネットワークによる大容量・低遅延・多接続性を活用する大規模センサデータ処理

この中でも特にデータが内包する『地理情報』『位置情報』に着目し、そのデータの分布、すなわち偏在性と遍在性に着目した様々なアルゴリズムや応用分析手法を研究しています。

### Labo Reader: 横山 昌平

* 東京都立大学システムデザイン学部情報科学科准教授
* 国立情報学研究所客員准教授
* 東京大学生産技術研究所リサーチフェロー
* 日本データベース学会理事

## メッセージ {#Message}

<div class="post-list">
    {% for post in site.posts %} 
        {% if post.about %}
    <ul>
        <li class="wow fadeInLeft" data-wow-duration="1.5s">
            <a class="zoombtn" href="{{ site.url }}{{ post.url }}">{{ post.title }}</a>
            <p>{{ post.excerpt }}</p>
            <a href="{{ site.url }}{{ post.url }}" class="btn zoombtn">Read More</a>
        </li>
    </ul>
        {% endif %}
    {% endfor %}
</div>

## アクセス {#Message}

・・・