---
layout: post
current: post
cover: 
navigation: True
title: 이 블로그에 글쓰기
date: 2020-03-06 00:00:00
tags: [story]
class: post-template
subclass: 'post tag-getting-started'
author: Hahn
---

블로그 쓰기
난 소프트웨어 개발자도 아니고, 컴퓨터 만지는 것을 아주 아주 좋아하는 것도, 능숙한 것도 아니다.
이 블로그에 글을 쓰기 위해서는 뭘 좀 해야하는데, 그게 귀찮아서 워드프레스 같은 블로그 도구를 이용하려다가도
몇 가지 재미있는 포인트들이 있어서 계속 쓰게된다.

이 블로그가 web-site로 생성되는 과정을 정확하게 이해하지 못하지만 내가 알고 있는 수준으로 설명을 해본다.
메모장 같은 텍스트에디터인 Vim을 열고 적는다. 그리고 파일로 저장한다.
이 파일은 Jekyll이라는 simple하고 static한 site를 개발하는 툴(규칙이 있으며 어떤 명령에 따라 수정되고 생성되는 폴더와 파일 더미들)을 통해 web-site로 만들어진다. 
site를 개발하는 툴은 결국 web-site에 보일 html파일을 만들어내는 기능을 한다.

simple하고 static한 site를 만들어 내는 것을 목적으로 하지만 그래도 너무 허전하면 재미가 없어서
여러사람들이 여러 다양한 theme를 만들어서 공유한다. 이 블로그는 Jasper2 theme를 이용하였다. 
theme를 내가 생각하는 방향에 맞게 수정을 좀 하게된다. 이때 초보자 수준의 html, Markdown 문법을 알면 조금 편하다.^^*  

site를 만들었으면 Web에 올려야하는데 이때 서버 공간을 github가 제공해주는 것을 쓰고 있다. 
그래서 git을 좀 알아야한다. 개발자들이 프로젝트하면서 버전관리하는 수준에는 못미치더라도
역시 초보자 수준으로는 알아야한다. 

theme가 좀 단순하면 파일을 저장한 PC에서 html을 생성하여 github에 올리면 된다. 
뭐라도 기능을 넣으려면 build-up 하는 과정에서 여러 pluge-in이 필요하다. 
그런데 PC OS의 보안상 뭔가 안되는 것들이 많다. 그래서 github에는 build-up 전의 파일들만 올리고
build-up은 Travis라는 것을 이용한다. Travis에는 지정된 github repository에 변동이 있으면 자동으로 build-up을 해서 site를 생성한다.

위의 과정들을 정확한 용어로 표현하거나 정확한 기능을 설명할 수는 없다. 왜냐하면 난 잘 모르고 큰 관심사가 아니다.^^*
build-up이 뭐하는 건지도 모른다. 그냥 Jekyll의 규칙에 따라 여러 파일들과 요소를 결합하여 html파일을 만든다? 라고 생각하고 있다.

목적도 없고, 게으르기도 하여 이 블로그를 거의 1년에 1개 정도 작성하고 있다. 
재미있는 포인트는 1년 사이에 여러 환경이 바뀌어 있다는 것이다.
2020년 첫 블로그를 적을 때 작년에 했던 것처럼 되지 않았다. 다음과 같은 변화가 있었기 때문이다.

1) MacOS가 Catalina로 업데이트 되면서 기본 shell이 Bash shell에서 Z shell로 바뀌었다. 
 두가지 차이점을 잘 모르고, 기본 shell을 다시 Bash로 바꿔서 쓸수도 있겠으나 대세를 따르고자하는 마음으로 Z shell을 써보기로 하였다. 
 여러 설정을 다시 해야했다. 
2) github 요구 비밀번호 보안수준이 높아져서 비밀번호를 바꿔야했다. 
 정확하게 찾아보지는 않았지만 비밀번호를 바꾸니 여러가지 손을 봐줘야했다. 특히 github와 Travis간 자동연동을 위해 보안 Token값 같은 것을 바꿔줘야했다.
 꼭 이문제 때문인지는 모르지만 어쨌던 Authentification관련 에러가 나서 그런가보다 하고 Token값을 다시 설정했더니 에러가 사라졌다.
3) 그 밖에도 여러 군데서 뭔가 보안이 강화됐는지 중간중간 설정해야하는 것들이 많았다. 

Simple & Static 사이트라서 다른 것들이 변화하면 거기에 맞춰져야하는게 좀 하기 싫다가도 재미가 있다. 
1년 사이에 이것은 이렇게 바뀌었고, 저것은 저렇게 바뀌었네 하면서 말이다. 
마치 자동차를 1970년형 포니를 몰고 있는데 환경 규제가 바뀌어서 엔진에 뭘 처리를 해줘야하고, 와이퍼는 규격이 바뀌어서 뭘 통채로 바꿔야하고 이런 기분이다. 

블로그가 어떻게 생성되는지는 크게 관심없는데,
Static을 하나 놓고 바뀌어 가는 것들을 맞춰나가다 보니 이것도 묘한 재미가 있어서 기록으로 남겨본다. 















































