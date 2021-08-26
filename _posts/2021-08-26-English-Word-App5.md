---
bg: "tools.jpg"
layout: post
title:  "영어단어 암기를 도와주는 앱 개발(최종)"
crawlertitle: "About Android"
summary: "영어단어 어플 개발"
date:   2021-03-01 19:24:30 +0700
categories: posts
tags: ['Android']
author: ImuB
comments: ture
---
프로젝트가 엎어졌다.... raw 파일 데이터를 읽어와서 단어 배열을 저장하고 불러오는 방식의
Ver 1.0을 구글 플레이에 배포하고 난 뒤 내장DB를 활용하는 방식의 Ver 2.0을 만들어 배포할려고 Android Studio에서 코드를 되돌리기 위해 Git revert를 사용해서 해당 커밋 시점으로 돌렸으나 그게 실수였는지 Gradle이 망가지면서 아예 프로젝트 자체를 사용할 수 없게 되어 버렸다...

이번 사건을 반면교사 삼아서 다신 프로젝트를 잃을 일 없게 내가 무슨 잘못을 했는지, 어떻게 살릴수있는지에 대해서 공부해봐야겠다.

1. git revert, reset에 대해서 확실히 개념 익히기
2. Android Studio Gradle에 대한 이
