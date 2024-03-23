---
publishDate: 2024-03-23T18:00:00+09:00
author: Takahiro Natsume
title: About ASSETPRICEJP
excerpt: This add-on provides google apps script to retrieve prices of Japanese stocks and mutual funds.
image: ~/assets/images/spreadsheets-sample.png
category: Document
tags:
  - assetpricejp
# metadata:
#   canonical: https://astrowind.vercel.app/get-started-website-with-astro-tailwind-css
---

## ASSETPRICEJP 使い方

Add-on をインストールします。
スプレッドシート内のセルに以下の式を入力することにより株価、基準価格を取得することができるようになります。
これは、アドオン内に内包の**GASの関数**を利用して日本株、投資信託の価格を取得しています。

### 日本株の株価取得の方法

スプレッドシートのセルで(例、ソフトバンクの場合)は、**_’=ASSETPRICEJP('JP', '9984')’_**とします。

### 投資信託の基準価格の取得方法

スプレッドシートのセルで(例、投資信託協会の投資信託全世界株式:オールカントリーの場合)は、**_'=ASSETPRICEJP('TOSHIN', 'JP90C000H1T1')'_**とします。
