---
bg: "tools.jpg"
layout: post
title:  "영어단어 암기를 도와주는 앱 개발(3)"
crawlertitle: "About Android"
summary: "영어단어 어플 개발"
date:   2021-01-30 15:24:30 +0700
categories: posts
tags: ['Android']
author: ImuB
---

#### '21.1.30 앱 개발 완료

전 포스팅에서 말했던 hwp에 있는 단어들을 다음과 같은 python언어로 데이터를 다듬었다.
![python code]({{ site.images | relative_url }}/Python-code.png)

이게 완벽하게 단어와 뜻을 구분짓지는 못하지만 거의 대부분을 원하는대로 분리시켜준다. 
이렇게 데이터를 가공한 뒤에 Android 프로젝트 raw폴더에 넣어서 활용할 것이다. 이후에는 구분자를 이용해서 단어와 뜻을 따로 변수에 담아서 출력해주어 어플을 개발하였다. 

##### 실제 어플 동작화면

![실동작화면1]({{ site.images | relative_url }}/android_main.png){: width="200" height="200" style="display: inline; margin-left: 5em"}![실동작화면2]({{ site.images | relative_url }}/android_difficultly.png){: width="200" height="200" style="display: inline; margin-left: 5em"}

#### 미완점
1. 좌상단에 있는 환경설정 버튼 미구현
2. 이전 단어를 보고 다음 단어를 가면 랜덤으로 보이는 현상
3. 단어를 난이도별로 구분짓지 않았음 사실상 난이도 기능 무쓸모
4. 깔끔하게 단어를 다듬지 못해서 중간중간 이상한 내용 출력

#### 추가할 기능
1. 환경설정 버튼에서 배경화면 색 변경 기능
2. DB를 활용하여 원하는 단어를 추가 또는 삭제할 수 있는 기능
* * * * *
참고로 프로젝트 계획 당시 내장DB를 활용하여 개발하려 했으나 그냥 파일을 불러와서 변수로 출력해도 상관없지않을까 라는 생각이들어 파일을 활용했다. ~~사실 어려워서~~
