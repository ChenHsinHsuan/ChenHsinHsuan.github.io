title: "Android Support Library 用途"
date: 2015-05-15 15:05:40
category: Android
tag: [Android, Support Library]  

---


開發Android 的過程常爬到文件上註明 support library的相關設定，

但是對於Support Library的作用很不明白，

爬完文章後大致整理如下：

版本
---
---
目前有v4, v7 , v13 等三種 Support Library


作用
---
---
可以讓版本較低的Android設備，透過Support Library 去使用Android新版本才有的功能


差異
---
---
v4
---

於Android1.6 (API lever 4) 以上版本使用

包含了  Fragment，NotificationCompat，LoadBroadcastManager，ViewPager，PageTabAtrip，Loader，FileProvider 等功能

詳細支援功能請參考  [Support Library v4](http://developer.android.com/reference/android/support/v4/app/package-summary.html)

v7
---
於Android2.1(API level 7) 以上版本使用

但是v7 繼承於 v4，所以兩個都要下載喔

v7部分多了很重要的  ActionBar


v13
---

於android 3.2及更高版本所使用

通常用於平板開發




