---
layout: page
title: Pohjoismainen matematiikka&shy;kilpailu
url: /PM/
description: >-
  Pohjoismainen matematiikkakilpailu sijoittuu vaikeustasoltaan kansallisten
  kilpailujen ja matematiikkaolympialaisten v�liin. Osallistujat ratkovat
  teht�vi� yht� aikaa kukin omassa koulussaan. Kilpailu on yksi t�rke� n�ytt�
  valittaessa joukkuetta matematiikkaolympialaisiin. T�ll� sivulla on aiempien
  kilpailujen teht�vi�, ratkaisuja ja tulostietoja.
kilpailut:
  - vuosi: 2019
    tehtavat: "2019/PM2019.pdf"
    ratkaisut: "2019/PM2019r.pdf"
  - vuosi: 2018
    tehtavat: "2018/PM2018.pdf"
    tulokset: "2018/PM2018tul.pdf"
  - vuosi: 2017
    tehtavat: "2017/PM2017.pdf"
    tulokset: "2017/PM2017tul.pdf"
  - vuosi: 2016
    tehtavat: "2016/PM2016.pdf"
    ratkaisut: "2016/PM2016r.pdf"
    tulokset: "2016/NMC2016res.pdf"
  - vuosi: 2015
    tehtavat: "2015/PM2015.pdf"
    ratkaisut: "2015/PM2015r.pdf"
    tulokset: "2015/NMC2015res.pdf"
  - vuosi: 2014
    tehtavat: "2014/PM2014.pdf"
    ratkaisut: "2014/PM2014r.pdf"
    tulokset: "2014/NMC2014res.pdf"
  - vuosi: 2013
    tehtavat: 2013/PM2013.pdf
    ratkaisut: 2013/PM2013r.pdf
    tulokset: 2013/NMC2013res.pdf
  - vuosi: 2012
    tehtavat: 2012/PM2012.pdf
    ratkaisut: 2012/PM2012r.pdf
    tulokset: 2012/NMC2012res.pdf
  - vuosi: 2011
    tehtavat: 2011/PM2011.pdf
    ratkaisut: 2011/PM2011r.pdf
    tulokset: 2011/PM2011tul.pdf
  - vuosi: 2010
    tehtavat: 2010/PM2010.pdf
    ratkaisut: 2010/PM2010r.pdf
    tulokset: 2010/PM2010tul.pdf
  - vuosi: 2009
    tehtavat: 2009/PM2009.pdf
    ratkaisut: 2009/PM2009r.pdf
    tulokset: 2009/NMC2009res.pdf
---

## Yleist�

Pohjoismainen matematiikka&shy;kilpailu on kouluesimerkki pohjoismaisesta
joustavasta tavasta hoitaa asioita. Kilpailuja on k�yty vuodesta 1987,
kun todettiin, ett� kansallisten kilpailujen ja
matematiikka&shy;olympialaisten v�liin tarvitaan sopivan&shy;tasoinen kisa.
J�rjestysvuoro kiert�� k��nteisess� ruotsinkielisen maannimen
mukaisessa j�rjestyksess� osallistuvissa maissa, ja kilpailu
j�rjestet��n yht'aikaa kunkin kilpailijan omassa koulussa.
Pohjoismaisessa matematiikka&shy;olympialaisissa noudatetaan k�yt�nn�ss�
vakiintuneita [k�yt�nt�j� ja s��nt�j�](nmcrules.html).

Suomen enint��n 20 edustajaa Pohjoismaiseen matematiikka&shy;kilpailuun
valitaan olympia&shy;valmennukseen osallistuvien ja Lukion
matematiikka&shy;kilpailussa menestyneiden joukosta. Valittuihin ja heid�n
kouluihinsa otetaan yhteytt� kirjeitse tai s�hk�posteitse joitakin
vikkoja ennen kilpailua. Kilpailu on yksi t�rke� n�ytt�, kun valitaan
joukkuetta kes�n kansainv�lisiin matematiikka&shy;olympialaisiin ja
henkil�it� toukokuiselle joukkeen valinta- ja valmennusviikolle.

Tanskan matematiikka&shy;olympia&shy;valmennus yll�pit�� Pohjoismaisen
matematiikka&shy;kilpailun [virallista kotisivua](http://www.georgmohr.dk/nmcperm/).
Sielt� l�ytyv�t mm. kaikki kilpailuteht�v�t ja ratkaisut
englanninkielisin� ja useiden kilpailujen teht�v�t eri pohjoismaisilla
kielill�.

## Teht�v�t ja ratkaisut

Vuosien 1987-1994 teht�v�t ja ratkaisut ovat tarjolla kirjassa
_Matti Lehtinen: Matematiikan olympiakirja._ N�iden
vuosien [teht�v�t](nmct87_94.pdf) ja [ratkaisut](nmcr87_94.pdf) saa my�s
oheisista linkeist�.

[Vuosien 1995-2016 teht�v�t ja ratkaisut](nmckaikki.pdf) ovat
ladattavissa yhten� tiedostona pdf-muodossa. 

## Menneet kilpailut

Alla olevassa taulukossa on tietoa menneist� kilpailuista vuodesta 1995 l�htien.

<div class="list-group">
{% assign c = 'class="col-xs-3 col-sm-2 col-md-1"' %}
<div class="row list-group-item">
<div {{ c }}><strong>Vuosi</strong></div>
<div {{ c }}><strong>Teht�v�t</strong></div>
<div {{ c }}><strong>Ratkaisut</strong></div>
<div {{ c }}><strong>Tulokset</strong></div>
</div>
{% for k in page.kilpailut %}
<div class="row list-group-item">
<div {{ c }}>{{ k['vuosi'] }}</div>
<div {{ c }}>{% if k['tehtavat'] != null %}<a href="{{ k['tehtavat'] }}">pdf</a>{% endif %}</div>
<div {{ c }}>{% if k['ratkaisut'] != null %}<a href="{{ k['ratkaisut'] }}">pdf</a>{% endif %}</div>
<div {{ c }}>{% if k['tulokset'] != null %}<a href="{{ k['tulokset'] }}">pdf</a>{% endif %}</div>
</div>
{% endfor %}
{% assign vt = "2008 2007 2006 2005" | split: " " %}
{% for v in vt %}
<div class="row list-group-item">
<div {{ c }}>{{ v }}</div>
<div {{ c }}><a href="{{ v }}/PM{{ v }}.ps">ps</a> <a href="{{ v }}/PM{{ v }}.pdf">pdf</a></div>
<div {{ c }}><a href="{{ v }}/PM{{ v }}r.pdf">pdf</a></div>
<div {{ c }}><a href="{{ v }}/PM{{ v }}tul.pdf">pdf</a></div>
</div>
{% endfor %}
{% assign vt = "2004 2003 2002" | split: " " %}
{% for v in vt %}
<div class="row list-group-item">
<div {{ c }}>{{ v }}</div>
<div {{ c }}><a href="{{ v }}/PM{{ v }}.ps">ps</a> <a href="{{ v }}/PM{{ v }}.pdf">pdf</a></div>
</div>
{% endfor %}
{% assign vt = "2001 2000 1999 1998 1997 1996 1995" | split: " " %}
{% for v in vt %}
<div class="row list-group-item">
<div {{ c }}>{{ v }}</div>
<div {{ c }}><a href="{{ v }}/PM{{ v }}.ps">ps</a> <a href="{{ v }}/PM{{ v }}.pdf">pdf</a></div>
<div {{ c }}><a href="{{ v }}/PM{{ v }}r.ps">ps</a> <a href="{{ v }}/PM{{ v }}r.pdf">pdf</a></div>
</div>
{% endfor %}
</div>
