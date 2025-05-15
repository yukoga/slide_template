---
marp: true
theme: default
style: | 
    @import url('https://fonts.googleapis.com/css?family=Noto+Sans+JP&display=swap');
    section.title {
        font-family: 'Noto Sans JP', sans-serif;
        justify-content: center;
        text-align: left;
    }
    section {
        font-family: 'Noto Sans JP', sans-serif;
        justify-content: start;
    }
    div.mermaid {
        all: unset;
        /* transform: scale(1.1);  for pdf */
        transform: scale(1.7);  /* for html */
        transform-origin: left center;
    }
    div.mermaid .nodeLabel {
        font-size: 10px; /* for pdf */
        font-size: 12px; /* for html */
    }
    img[alt~="center"] {
        display: block;
        margin: 0 auto;
    }
    .mycontents {
        display: flex;
        flex-wrap: nowrap;
        justify-content: center;
    }
    .mycard {
        width: calc(100% / 2);
    }
    .mycard-left {
        width: calc(80% / 2);
    }
    .mycard-right {
        width: calc(120% / 2);
    }    
    table {
        font-size: 18pt;
    }
    thead th {
        background-color: #DDDDDD;
        border-color: #CCCCCC;
    }
    tbody tr td:first-child {
        background-color: #EEEEEE;
        border-color: #CCCCCC;
    }
    tbody tr td:nth-child(n+2) {
        background-color: #FFFFFF;
        border-color: #CCCCCC;
    }
    tbody tr:last-child {
        background-color: rgba(0, 0, 0, 0.0);
        border-style: solid;
        border-width: 0;
    }

backgroundImage: url('https://marp.app/assets/hero-background.svg')
size: 16:9
paginate: true

---
<!--
_class: title
_paginate: false
_color: white
-->
# Presentation title
&nbsp; &nbsp; 20th Feb, 2025 / Author
![bg opacity:.9 brightness:0.4](./img/titlebackground.png)

---
## Contents 


### - Contents 1 
- subtitle / subtitle / subtitle
### - Contents 2
- subtitle / subtitle / subtitle
### - Content 3
- subtitle / subtitle / subtitle
### - Content 4
- subtitle / subtitle / subtitle

---
<style scoped>
    h1 {
        position: absolute;
        top: 300px;
    }
</style>

# Section title

---

## Slide title
![h:480 center](./img/john-schnobrich-FlPc9_VocJ4-unsplash.jpg)

<!--
_footer: 'Source [Reference link]([http://igo/SoT-Training](https://unsplash.com/photos/person-using-laptop-FlPc9_VocJ4))'
-->

---
![bg opacity:.9](./img/john-schnobrich-FlPc9_VocJ4-unsplash.jpg)

<!--
_footer: 'Source [Reference link]([http://igo/SoT-Training](https://unsplash.com/photos/person-using-laptop-FlPc9_VocJ4))'
-->

---

## Slide with bullet points 
- Topic A ... xxxxx.  
- Topic B ... xxxxx.
- Topic C ... xxxxx.
- Topic D ... xxxxx.

---
<style scoped>
    .image-container {
        display: flex;
        /* Flexboxレイアウトを使用 */
        justify-content: flex-start;
        /* 左寄せ */
        align-items: center;
        /* 垂直方向中央揃え */
        width: 100%;
        /* コンテナを画面幅いっぱいに */
    }

    .image-container img {
        width: 50%;
        /* 各画像の幅をコンテナの30%に設定 */
        height: auto;
        /* 高さは自動調整 */
        object-fit: contain;
        /* 画像がコンテナ内に収まるように調整 */
        margin: 0 1.666%;
        /* 左右に均等なマージンを設定（3つ合わせて5%） */
    }
</style>

## Slide with two images

<div class="image-container">
    <img src="./img/john-schnobrich-FlPc9_VocJ4-unsplash.jpg" alt="report1">
    <img src="./img/john-schnobrich-FlPc9_VocJ4-unsplash.jpg" alt="report2">
</div>

<!--
_footer: 'Source [Reference link]([http://igo/SoT-Training](https://unsplash.com/photos/person-using-laptop-FlPc9_VocJ4))'
-->


---
<style scoped>
    h1 {
        position: absolute;
        top: 300px;
    }
</style>

# Section title

---

## Slide with a table 

<div class="mycontents">

|Items|Description|Limits|Use cases|
|---|---|---|---|
|Item A|AAAAAAAAA|AAAAAAAAA|AAAAAAAAA|
|Item B|BBBBBBB|BBBBBBB|BBBBBBB|
|Item C|CCCCCCC|CCCCCCC|CCCCCCC|
|Item D|DDDDDDD|DDDDDDD|DDDDDDDD|

</div>

<!--
_footer: 'Source [Reference link]([http://igo/SoT-Training](https://unsplash.com/photos/person-using-laptop-FlPc9_VocJ4))'
-->

---
<style scoped>
    h1 {
        position: absolute;
        top: 300px;
    }
</style>
# Section title

---
## Slide title 
- XXXXX.
    - YYYYY.
    - ZZZZZ.
        - AAAAA.

---
## Slide title 
- XXXXX.
    - YYYY.
    - ZZZZ.  
        - AAAA.
    - <span style="color: red;">AAAA.</span>

---
<style scoped>
    h1 {
        position: absolute;
        top: 300px;
        color: rgba(255, 255, 255, 0.65);
        font-size: 200%;
    }
</style>
<!--
_paginate: false
_color: rgba(255, 255, 255, 0.65)
-->

# Thanks. 

![bg opacity:.9 brightness:0.8](./img/45025977691_0103ce74f0_k.jpg)
<!--
_footer: 'Photo by [Tobi Gaulke](https://www.flickr.com/photos/gato-gato-gato/45025977691)'
-->
