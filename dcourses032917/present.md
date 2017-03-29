---
## Basics for Front-end developer
### C001 網站前端入門
#### twngo.xyz @ TAHR KS

<!-- .slide: data-background="https://i.imgur.com/ZZj54mf.jpg" -->

---
## 今日課程架構
#### 重新了解互聯網 
### 認識 git 
####  DNS 
#### 瀏覽器呈現語言
### html/CSS 

---
# 本日重點 1 
## What is git ? 
### 新手必學指令
init

add

commit

---
## 實作案例  1
### github 操作
#### 新手必學指令
clone https://github.com/twngo/dcourses.git

push

pull 


---
## 互聯網 
#### What is "internet"?
[Map of the internet ](https://qz.com/se/map-of-the-internet/) --Quartz  2016.10


---
#### Domain Name Service 
![](http://i.imgur.com/TA1gfPj.png)
<!-- .slide: data-background-color="#fff" -->


---
- Doman Name registrar : [gandi](https://gandi.net); [godaddy](https://godaddy.com)
- gTLD [價格表](https://www.gandi.net/domain/price/info)
![gandi domain price](https://i.imgur.com/ALrC9cR.png)(https://www.gandi.net/domain/price/info)

---
## DNS 設定
以Gandi為例
root zone

- Cname
- A, AAA
- MX
- SPF, TXT

---
## 資安小提醒
DNS cache pollution / DNS cache poisoning
![](http://2we26u4fam7n16rz3a44uhbe1bq2.wpengine.netdna-cdn.com/wp-content/uploads/091515_2139_Attacksover2.jpg)

[How to Prevent DNS Attacks](http://www.esecurityplanet.com/network-security/how-to-prevent-dns-attacks.html)


---
## 什麼是「Front-end」（前端）？
![](https://content-static.upwork.com/blog/uploads/sites/3/2015/05/05110037/Front-end-dev1.png)


---
![web browser](https://assets.pcmag.com/media/images/514315-the-best-browsers-of-2016.jpg?thumb=y&width=810&height=456)


---
## 瀏覽器端運行的語言
- html (hyper text mark language)
- CSS (Cascading Style Sheets )
- javascipt

![](https://www.frontendhandbook.com/images/web-tech-employed.jpg)

---
# html5 
文件基本結構(dcourses/c001/index.html)
```<html>
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Title of the document 文件名稱</title>
<link rel="stylesheet" href="css/style.css">
</head>
<body>
Content of the document......
</body>
</html>
```

---
## 必學 html 
#### 常用標籤(Tags)與屬性（Attributes）
```<body>
<a href="">
<img src="" atl="圖片說明...">
<h1><h2><h3>
<p id="para01">
<br>
<ul><ol><li>

```
[實用作弊小抄](HTML5-cheat-sheet.pdf)

---
# 今日重點
## 實作案例  2
小試身手：html+CSS實作
請自力編寫完成一個html檔案
其中須包括：
1. 3個``<a>`` 超連結標籤
2. 3張圖片 ``<img>`` 標籤
3. 2個文字段落 ``<p>``
4. 運用列表``<ul>`` or ``<ol>`` 標籤功能，列表中至少有3件東西或事物

---
# CSS3 
### 語法與選擇器重要觀念
```
tag {}
#id {}
.class {}
tag .class #id {}
tag : #id {}

```
[實用語法規則彙整](CSS2-Help-Sheet.pdf)
[CSS重點規則-14頁](css3-mega-cheat-sheet-A4.pdf)

---
# 今日重點
## 實作案例  ３
透過CSS 來修改上個案例中的html 的版面呈現
除了在<head></head>加入CSS link 之外，不可改動　index.html　其它部份
請自力編寫 style.css 檔案
其中須包括：
1. 挑出3個選擇器
2. 每個選擇器中，必須至少含有2個規則命令


---
## [Bootstrap](https://getbootstrap.com/) 
### responsive, mobile first


---
## browser web developer tool
### ctrl + shift + i



---
## 靜態網頁 v. 動態網頁

- 資料庫使用

---
## 實際案例示範 
申請免費網站主機服務

- [byet.host](https://byet.host/free-hosting) 內建CMS選項最多

- [000webhost](https://www.000webhost.com)  僅支援wordpress / 靜態網頁


---
## 瀏覧器外掛分析工具--Wappalyzer
![](https://i.imgur.com/Uh8n93T.png)


---
## 瀏覧器外掛分析工具--Shodan
![](https://i.imgur.com/Uh8n93T.png)



---
#### 歡迎加入協作交流平台--[glip](https//glip.cm)
![](https://i.imgur.com/lwo4xt0.png)
[glip 使用入門](https://medium.twngo.xyz/%E5%8D%94%E4%BD%9C%E5%B9%B3%E5%8F%B0%E6%9C%8D%E5%8B%99-glip-%E4%BB%8B%E7%B4%B9-b115ec9e891d)

