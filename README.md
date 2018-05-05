# 草尼馬 Line Bot

[![codebeat badge](https://codebeat.co/badges/8606dde5-df3a-4bae-beb5-0c8b46f48ac3)](https://codebeat.co/projects/github-com-tonyyang924-mudhorse-line-bot-master)

<img src="./mudhorse.jpg" width="256" height="256" />

LINEID: @sgc9537d

![](mudhorse_qrcode.png)

### 指令

## androidweekly
爬androidweekly.net當週前5筆新文章。

## 591
爬591租屋網的物件，每次回更新時間最新的前五筆。

<span style="color:red; font-weight: bold;">目前只支援雙北</span>

格式
```
591 位置=[新北市,台北市,...,三重區,蘆洲區,大安區] 類型=[整層住家,獨立套房,分租套房,雅房,車位,其他] 租金=[最低價格,最高價格] 坪數=[最低坪數,最高坪數]
```

範例:
```
591 位置=新北市 類型=整層住家 坪數=20,30

591 位置=三重區 租金=10000,23000 類型=整層住家
```
![](./screenshot/1.png)
