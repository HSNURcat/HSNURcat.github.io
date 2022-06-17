---
layout: post
current: post
cover:  assets/built/images/javascript.png
navigation: True
title: Javascript 타이머
date: 2022-06-12 21:54:00 +0900
tags: [javascript]
class: post-template
subclass: 'page-template'
author: HSNURcat
---

1. setTimeout메서드 : 일정 시간이 흐른 후 1번만 호출되는 함수 등록  
```js
setTimeout(function() {
    console.log(new Date());
}, 2000);
```

2. setInterval메서드 : 지정된 시간마다 반복해서 호출되는 함수 등록  
```js
setInterval(function() {
    console.log(new Date());
}, 1000);
```