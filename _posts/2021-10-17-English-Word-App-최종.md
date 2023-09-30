---
bg: "tools.jpg"
layout: post
title:  "'짬내서 영단어' 앱 개발(최종)"
crawlertitle: "About Android"
summary: "영어단어 어플 개발"
date:   2021-10-17 19:24:30 +0700
categories: posts
tags: ['Android']
author: ImuB
comments: ture
---
![스토어출시1]({{ site.images | relative_url }}/앱출시(1).jpg){: width="200" height="200" style="display: inline; margin-left: 5em"}![스토어출시2]({{ site.images | relative_url }}/앱출시(2).jpg){: width="200" height="200" style="display: inline; margin-left: 5em"}

마지막 영단어 앱 개발 포스팅을 올린지 약 3개월이 지났다.
정확한 방향없이 개발을 하다보니 개발기간이 길어졌다.
프로젝트를 마치면서 느끼고 생각했던것은 따로 포스팅해서 정리하겠다.

먼저 중간에 하려던 DB를 넣는다던지했던 기능들은 모조리 빼고 원래
생각했던 파일데이터를 이용한 어플을 개발했고

이 어플의 기능은 단순하다.
+ **영단어 종류 선택** 
+ **좌 우를 눌러서 단어 넘기기**  
+ **뜻 가리기**  

이렇게 구성된 어플이고 여기서 좀 더 업데이트할 기능은
- **파일데이터를 DB화하여 내장DB 활용하기.**
- **시험기능을 추가하여 맞추게되면 해당단어 노출X**
- **총 단어에서 외운단어 progress_bar를 활용 시각화**
- **배경색깔 개인기호에맞게 바꿀수있는 기능 추가**  

정도로 업데이트를 할 예정이다.
