---
layout: page
title: '広島の楽しい100人 勝手にまとめ'
permalink: /hiroshima100nin/
events:
  -
    name: 第1回
    date: 2014年9月24日
    url: https://www.facebook.com/events/1391423294435567/
    speakers:
      -
        name: "[澤井 律子](https://www.facebook.com/sawairitsuko)"
        organization: "[ひろしま着物遊び](http://www.kimonoasobi.info)"
      -
        name: "[沖本 和久](https://www.facebook.com/okazuhisa)"
        organization: "[フリップミュージック](http://www.frippmusic.com/)"
      -
        name: "[溝口 徹](https://www.facebook.com/toru.mizoguchi.142)"
        organization: "[横川シネマ](http://yokogawa-cine.jugem.jp/)"
      -
        name: "[モリマコ](https://twitter.com/morimako1)"
        organization: "[ケンダマロックカフェ](http://www.kendamarock.com/)"
  -
    name: 第2回
    date: 2014年11月26日
    url: https://www.facebook.com/events/381577058675130/
    speakers:
      -
        name: "[ゴトウイズミ](https://www.facebook.com/izumi.goto.353)"
        organization: "[ヲルガン座](http://www.organ-za.com/)"
      -
        name: "[篠原 良一郎](http://about.me/ryoichiro_shinohara)"
        organization: "[うちの婆様](https://www.facebook.com/basama88/)"
      -
        name: "[河口 知明](https://www.facebook.com/kohguchi)"
        organization: "[コスカレード](http://cosquerade.jp/)"
      -
        name: "[槌本 裕二](https://www.facebook.com/tsuchim)"
        organization: "[栄諧情報システム株式会社](http://eikai.co.jp/)"
  -
    name: 第3回
    date: 2015年1月24日
    url: https://www.facebook.com/events/744646872281891/
    speakers:
      -
        name: "[藤井智康](https://www.facebook.com/tomoyasu.fujii)"
        organization: "[デロリアンＥＶ化計画](http://delorean.tumblr.com/)"
      -
        name: "[塩崎 周司](https://www.facebook.com/Shiozy)"
        organization: ""
      -
        name: "[吉野 瞬](https://www.facebook.com/shun.yoshino1)"
        organization: "[ART GALLERY シゲイノイエ](https://www.facebook.com/shigeinoie.1681)"
      -
        name: "[チャーリー ローズ](https://www.facebook.com/charlie.hormann)"
        organization: "[lovelovebycharlierose](http://charlieroselovelove.com/)"
  -
    name: 第4回
    date: 2015年3月28日
---


* [広島の楽しい100人](https://www.facebook.com/h100parson)

| 開催日 | 登壇者1 | 登壇者2 | 登壇者3 | 登壇者4 |
|--|--|--|--|--|
{% for event in page.events %}| <span class="event-date">{{ event.date }}</span> <span class="event-name">[{{ event.name }}]({{ event.url }})</span> | {% for speaker in event.speakers %} <span class="name">{{ speaker.name }}</span> <span class="organization">{{ speaker.organization }}</span> | {% endfor %}
{% endfor %}
