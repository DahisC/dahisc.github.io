---
title: Line Notify 處理服務綁定的套件
abbrlink: 63538
date: 2021-07-19 11:31:35
tags:
category: Portfolio
---

# 相關連結

- [NPM](https://www.npmjs.com/package/@dahisc/line-notify)
- [Github Repository](https://github.com/DahisC/line-notify)

# 關於此作品

> 這個作品主要是當時在撰寫 [水藍嗶啵鼠](https://dahisc.github.io/posts/63534/) 時要接 Line Notify 的過程中有很多設定與文件要看，後來乾脆索性自己開發一個套件專門解決這件事情，就像用 Node.js 中的 Passport 一樣；主要是解決將使用者與服務綁定的中間這段 Oauth 2 的認證過程。

- 2020/7 開發完成
- 主要使用了 express 中的路由功能實作，使用者只須引入套件後填入以下欄位即可串接服務
  1.  client_id
  2.  client_secret,
  3.  succeeded_route,
  4.  failed_route,

# 使用技術

|          |    技術／套件     |
| :------: | :---------------: |
| 後端框架 | Node.js + express |
| 部署環境 |        NPM        |
