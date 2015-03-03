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
        movie: "https://www.youtube.com/watch?v=RHGaHWtGGh4"
      -
        name: "[沖本 和久](https://www.facebook.com/okazuhisa)"
        organization: "[フリップミュージック](http://www.frippmusic.com/)"
        movie: "https://www.youtube.com/watch?v=TekB_ImULhM"
      -
        name: "[溝口 徹](https://www.facebook.com/toru.mizoguchi.142)"
        organization: "[横川シネマ](http://yokogawa-cine.jugem.jp/)"
        movie: "https://www.youtube.com/watch?v=bF_1xfnWoWc"
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
        movie: "https://www.youtube.com/watch?v=5tCXcLH4MhU"
      -
        name: "[篠原 良一郎](http://about.me/ryoichiro_shinohara)"
        organization: "[うちの婆様](https://www.facebook.com/basama88/)"
      -
        name: "[河口 知明](https://www.facebook.com/kohguchi)"
        organization: "[コスカレード](http://cosquerade.jp/)"
        movie: "https://www.youtube.com/watch?v=Pf9FavhLpdk"
      -
        name: "[槌本 裕二](https://www.facebook.com/tsuchim)"
        organization: "[栄諧情報システム株式会社](http://eikai.co.jp/)"
        movie: "https://www.youtube.com/watch?v=lVA0TO1OY6s"
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
    url: https://www.facebook.com/events/744646872281891/
    speakers:
      -
        name: "[竹中庸子](https://www.facebook.com/takenaka.yoko.3)"
        organization: "[特定非営利活動法人 もちもちの木](https://www.facebook.com/pages/%E7%89%B9%E5%AE%9A%E9%9D%9E%E5%96%B6%E5%88%A9%E6%B4%BB%E5%8B%95%E6%B3%95%E4%BA%BA-%E3%82%82%E3%81%A1%E3%82%82%E3%81%A1%E3%81%AE%E6%9C%A8/159545200813770?pnref=lhc)"
      -
        name: "[織田健司](https://www.facebook.com/kenji.oda.121)"
        organization: "[広島ものづくりジム](https://www.facebook.com/monogym?pnref=lhc)"
      -
        name: "[中村純](http://home.riise.hiroshima-u.ac.jp/~nakamura/)"
        organization: "[私とパンフルート](http://home.riise.hiroshima-u.ac.jp/~nakamura/AN/)"
      -
        name: "[平尾順平](https://www.facebook.com/jumpei.hirao)"
        organization: "[ひろしまジン大学](http://hirojin.univnet.jp/)"
---


* [広島の楽しい100人](https://www.facebook.com/h100parson)

<table class="h100nin">
{% for event in page.events %}
  <tr>
  <th><span class="event-date">{{ event.date }}</span> <span class="event-name"><a href="{{ event.url }}">{{ event.name }}</a></span></th>
  {% for speaker in event.speakers %}
    <td><span class="name" markdown="1">{{ speaker.name }}</span> <span class="organization" markdown="1">{{ speaker.organization }}</span></td>
  {% endfor %}
{% endfor %}
</table>
