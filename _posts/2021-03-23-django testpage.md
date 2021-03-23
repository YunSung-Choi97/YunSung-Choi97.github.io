---
layout: article
title: 여기가 제목인가? - Aside
categories : [Python/Django]
aside:
  toc: true

---


<br><br>
docker 컨테이너 연결을 하고 난 뒤 django 서버 셋팅하는 방법을 정리하였다. 데이터베이스 컨테이너와 웹서버 컨테이너를 연결하는 방법은 아래의 포스팅을 참고하면 될 것 같다.<br>
* 도커 컨테이너 연결 : https://devyurim.github.io/ubuntu/docker/2018/06/27/ubuntu-docker-6.html
<br><br>

도커 컨테이너 내에서 장고 서버를 구동하기 위한 셋팅 방법을 정리하였다. 장고 걸스 튜토리얼이 많은 도움이 되었다.<br><br>


> <subtitle> 1. django 프로젝트 생성 </subtitle>

장고 컨테이너 내부로 접속하여 장고 웹서버가 작동되는지 확인이 필요하다. 먼저 아래의 명령어를 실행하여 장고 프로젝트를 생성한다.<br>
{% highlight shell %}
$ django-admin startproject mysite .
{% endhighlight %}
<br>

