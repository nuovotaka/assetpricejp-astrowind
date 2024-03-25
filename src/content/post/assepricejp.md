---
publishDate: 2024-03-23T18:00:00+09:00
author: Takahiro Natsume
title: About ASSETPRICEJP
excerpt: This add-on inserts formulas into spreadsheet cells to obtain prices of Japanese stocks and mutual funds.
You can also use the function (ASSETPRICEJP) in the add-on to get the prices.
image: ~/assets/images/spreadsheets-sample.png
category: Document
tags:
  - assetpricejp
# metadata:
#   canonical: https://astrowind.vercel.app/get-started-website-with-astro-tailwind-css
---

このアドオンは、表計算のセルに数式を挿入して、日本の株式や投資信託の価格を取得します。
アドオン内の関数(ASSETPRICEJP)を使用して価格を取得することもできます。

# ASSETPRICEJP 使い方

Add-on をインストールします。
価格の取得方法は2種類あります。

1. スプレッドシート内のセルに以下の式を入力することにより株価、基準価格を取得することができるようになります。
   これは、アドオン内に内包の**GASの関数**を利用して日本株、投資信託の価格を取得しています。
2. アドオンのスライドを表示して日本株は４桁、投資信託は１２桁の英数字を入力してください。選択してセルに式を代入してくれます。

## アドオンを利用する方法

日本株の株価の場合は４桁、投資信託の場合は１２桁のISINコードを入力ください。
![HOW TO USE 1](~/assets/images/howtouse-1.png)

- ASSETPRICEJP > サイドバーの表示

![HOW TO USE 2](~/assets/images/howtouse-2.png)

- セルを選択するコードを４桁または、１２桁入力する

![HOW TO USE 3](~/assets/images/howtouse-3.png)

- 例、9984のソフトバンクを入力してみます。

![HOW TO USE 4](~/assets/images/howtouse-4.png)

- 2024/03/22 終値が表示されました。

## 直接、式をセルに代入する方法

### 日本株の場合

スプレッドシートのセルで(例、ソフトバンクの場合)は、**_’=ASSETPRICEJP('JP', '9984')’_**とします。

### 投資信託の場合

スプレッドシートのセルで(例、投資信託協会の投資信託全世界株式:オールカントリーの場合)は、**_'=ASSETPRICEJP('TOSHIN', 'JP90C000H1T1')'_**とします。
