---
title: BoonJot Fonts
subtitle: บุญจด ฟอนต์หรรษา
author: สังศิต ไสววรรณ
date: 2015/10/29
---

# ภาษาไทยมาตรฐาน (Standard Thai)

<div class="thai-pangram poem">

กีฬาบังลังก์  | ลำดับที่ ๑,๒๓๔,๕๖๗,๘๙๐
---------------------- | -------------------------
๏ จับฅอคนบั่นต้อง   | อาญา
ขุดฆ่าโคตรฃัตติยา     | ซ่านม้วย
ธรรมฤๅผ่อนรักษา     | ใจชั่ว โฉดแฮ
สืบอยู่เต็มศึกด้วย      | ฝุ่นฟ้ากีฬา กามฦๅ ฯ
๏ กตัญญูไป่พร้อม    | ปฐมฌาน
เกมส๎วัฒน์ปฏิภาณ     | ห่อนล้ำ
ทฤษฎีถ่อยๆ สังหาร   | เกณฑ์โทษ
โกรธจี๊ดจ๋อยจ่มถ้ำ      | อยู่เฝ้า “อตฺตา” ๚ะ๛

[สังศิต ไสววรรณ ๑๒ กรกฎาคม ๒๕๕๘](https://fontuni.com/articles/2015-07-12-thai-poetgram.html)
</div>

<small>ถึงหน้าตาจะขี้เล่น แต่บุญจดรู้เรื่องการวางตำแหน่งตัวอักษรและเข้าใจวิธีเขียนภาษาไทยมาตรฐานในเว็บบราวเซอร์สมัยใหม่นะ</small>

# ภาษาบาลี/สันสกฤต (Pali/Sanskrit orthography)

<p lang="pi-Thai">ฐาตุํ ญาติํ อุปฺปฏฺฐานํ ปุํลิงฺคํ วาปิํ ปํสุํ วฏฺฏุํ</p>

<small>บุญจดใช้เขียนบาลี/สันสกฤตใน HTML ได้ด้วย `lang="pi-Thai"` แต่ต้องใช้ CSS+JS ช่วยนิดหน่อยสำหรับบราวเซอร์รุ่นโบราณ</small>

~~~html
<p lang="pi-Thai">ฐาตุํ ญาติํ อุปฺปฏฺฐานํ ปุํลิงฺคํ วาปิํ ปํสุํ วฏฺฏุํ</p>
~~~

~~~css
body { font-feature-settings: "locl"; }
~~~

# ภาษาชาติพันธุ์ (Minority languages)

ปะเฺติ็ลฺ โฺญฺ็จฺ ปั็วฮฺ ทฺ็อง เปฺิ็ว มูํย แต็่ง เจฺํอ  
เปรฺิ่ห์ โจ๊่ เปฺี่ย โฺทร ม็่อง เติ็ง อาื ยาึ จือรฺุ การฺู

<small>บุญจดรับมือวิธีเขียนที่ซับซ้อนกว่าภาษาไทยมาตรฐานได้แต่กำเนิดอีกต่างหาก!</small>

# Thai Ligatures

ฤๅ ฦๅ ๏่่ ๏..

<small>อันนี้ของแถมสำหรับภาษาไทย เปิดใช้งาน Ligatures ได้ด้วย CSS</small>

~~~
ฤๅ ฦๅ ๏่่ ๏..
~~~

~~~css
body { font-variant: common-ligatures; }
~~~

# Mixed paragraph

<p style="font-size:24px; text-align:left;">
ฝุ่นน้ำท้องฟ้า ทุ่งหญ้าป้ำเป๋อ ชนชั้นกระฎุมพี เป่าปี่กตัญญู <span lang="pi-Thai">ฐาตุํ ญาติํ อุปฺปฏฺฐานํ ปุํลิงฺคํ วาปิํ ปํสุํ วฏฺฏุํ</span> ปะเฺติ็ลฺ โฺญฺ็จฺ ปั็วฮฺ ทฺ็อง เปฺิ็ว มูํย แต็่ง เจฺํอ เปรฺิ่ห์ โจ๊่ เปฺี่ย โฺทร ม็่อง เติ็ง อาื ยาึ จือรฺุ การฺู Quick zephyrs blow, vexing daft Jim. Do bạch kim rất quý, sẽ để lắp vô xương. „Fix, Schwyz!“ quäkt Jürgen blöd vom Paß. Voyez le brick géant que j'examine près du wharf Quel vituperabile xenofobo zelante assaggia il whisky ed esclama: alleluja! Queda gazpacho, fibra, látex, jamón, kiwi y viñas. Luís argüia à Júlia que «brações, fé, chá, óxido, pôr, zângão» eram palavras do português. Jove xef, porti whisky amb quinze glaçons d'hidrogen, coi! Laŭ Ludoviko Zamenhof bongustas freŝa ĉeĥa manĝaĵo kun spicoj. Høj bly gom vandt fræk sexquiz på wc Vår sære Zulu fra badeøya spilte jo whist og quickstep i min taxi. Pójdźże, kiń tę chmurność w głąb flaszy! Příliš žluťoučký kůň úpěl ďábelské ódy Kæmi ný öxi hér ykist þjófum nú bæði víl og ádrepa. Egy hűtlen vejét fülöncsípő, dühös mexikói úr Wesselényinél mázol Quitóban.
</p>

~~~css
body { font-kerning: normal; }
~~~

# Proportional & Tabular Figures

<span class="pnum">0123456789</span><br>
<span class="tnum">0123456789</span>

<small>Default is proportional.</small>

~~~html
<span class="pnum">0123456789</span><br>
<span class="tnum">0123456789</span>
~~~

~~~css
.pnum { font-feature-settings: "pnum"; }
.tnum { font-feature-settings: "tnum"; }
~~~

# Fractions

1&thinsp;&frac14; 5&thinsp;&frac12; 9&thinsp;&frac34; <span class="frac">1/3 2/3 1/8 3/8 5/8 7/8</span>

<p class="frac">
  123456789123456789/98765432109876543210
</p>

<small>BoonJot supports both pre-composed & arbitrary fractions.</small>

~~~html
1&thinsp;&frac14; 5&thinsp;&frac12; 9&thinsp;&frac34; <span class="frac">1/3 2/3 1/8 3/8 5/8 7/8</span>
<span class="frac">123456789123456789/98765432109876543210</span>
~~~

~~~css
.frac { font-feature-settings: "frac"; }
~~~

# Subscripts & Superscripts

H<sub>2</sub>O &times; 9.87<sup>654</sup> &#x2260; &radic;&pi; &divide; World<sup>3</sup>!

<small>You can easily write subscripts & superscripts with `<sub>` & `<sup>` elements, just enable BoonJot&rsquo;s features.</small>

~~~html
H<sub>2</sub>O &times; 9.87<sup>654</sup> &#x2260; &radic;&pi; &divide; World<sup>3</sup>!
~~~

~~~css
sub { font-feature-settings: "subs"; }
sup { font-feature-settings: "sups"; }
~~~

# Localized forms

<p lang="ro">Gheorghe, obezul, a reuşit să obţină jucându-se un flux în Quebec de o mie kilowaţioră.</p>

<small>Don&rsquo;t worry about old encoded texts, BoonJot can correct Romanian/Moldovan for you.</small>

~~~html
<p lang="ro">Gheorghe, obezul, a reuşit să obţină jucându-se un flux în Quebec de o mie kilowaţioră.</p>
~~~

# GitHub repository

[github.com/fontuni/boonjot](https://github.com/fontuni/boonjot)
