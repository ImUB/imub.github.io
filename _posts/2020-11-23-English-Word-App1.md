---
bg: "tools.jpg"
layout: post
title:  "'짬내서 영단어' 앱 개발(1)"
crawlertitle: "About Android"
summary: "영어단어 어플 개발"
date:   2020-11-23 22:19:47 +0700
categories: posts
tags: ['Android']
author: ImuB
comments: ture
---
### 개발 동기

4년제 컴퓨터공학과를 다니며 여러가지 프로젝트를 하겠다고 다짐 했지만 완성시킨 프로젝트가 단 하나도 없었다. 그래서 전공자라고 말하기 부끄러웠다. 하지만 지금이라도 다시 한걸음 한걸음 밟아가면 언젠가는 잘하지 않을까 라는 생각을한다. 그래서 첫 프로젝트를 개발해야겠다고 생각했고   그렇게 고민하다 생각한 첫 프로젝트가 영어단어 암기 어플이다. 영어공부도 해야되고 영어단어 암기를 돕는 앱 정도는 시중에도 많이있고 개발하기 크게 까다롭지 않을거라 판단하여 첫 프로젝트로 제격일거라고 생각했다.

### 개발 계획

## 1. 앱 UI 구성
![Repo Make]({{ site.images | relative_url }}/English-word-UI.png){: width="200" height="200" style="display: inline; margin-left: 5em"}![난이도 설정 페이지]({{ site.images | relative_url }}/English-word-Difficultly.png){: width="200" height="200" style="display: inline; margin-left: 5em"}

## 2. 앱 동작

1. activity_main.xml   
여기서는 3개의 버튼이 보이는데 환경설정, 난이도, 시험   
**환경설정**은 어플의 설정과 관련된 기능들이 담길 것이고 왼쪽에서 서랍형식으로 열릴것이다.   
**난이도는** activity_difficultly.xml로 화면이 넘어가서 해당 난이도 값을 받아오는 역할이다.   
**시험**은 단어 또는 뜻이 빈칸으로 생기며 스스로 시험을 볼 수있도록 도와주는 기능이다.

2. activity_difficultly.xml    
보는것과 같이 초급, 중급, 고급으로 나누어지고 거기에 맞는 데이터들을 activity_main으로 넘겨줄 화면이다.

### 마치며

여기서는 상세하게 계획을 얘기하지 않았다. 어떤 DB를 써야할지 어떻게 데이터를 파싱해올지 개발을 하기전에 그런 생각을 먼저하면 힘들어지기 때문에 일단 만들면서 닥쳐오는 시련을 극복하면서 관련 포스팅을 이어나가겠다.
