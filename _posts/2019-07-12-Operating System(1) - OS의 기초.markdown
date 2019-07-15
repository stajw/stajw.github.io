---
layout: post
title:  "Operating System(1) - OS의 기초"
date:   2019-07-12 17:52:55
author: Jinwoo Ahn
categories: OS
---
## OS의 기초
<span style="color:red">Operating System</span>, 즉 운영체제에 대해서 배우기 전에 반드시 알아야 할 것은 운영체제란 무엇인가?? 라는 것이다.  
운영체제는 컴퓨터 user와 컴퓨터 hardware 사이에서 중간자 역할을 하는 프로그램 정도로 정의할 수 있다.  
중간자라는 말이 살짝 애매하게 들릴 수도 있겠지만, 다음 운영체제의 목표를 보면 어느 정도 의미 파악이 수월할 것이다.
* __User program을 실행하고, user problem을 더욱 쉽게 해결하기 위함__
* __Computer hardware를 더욱 효과적인 방법으로 사용하기 위함__  

위와 같이 운영체제는 크게 2가지의 목표를 가지고 있다.  
그렇다면 운영체제와 하드웨어를 포함한 computer system의 구성요소는 어떻게 될까?  
1. Hardware  
CPU, 메모리, I/O devices들이 포함된다.
2. Operating System  
다양한 application들과 user들 사이에서 hardware의 사용을 컨트롤한다.
3. Application program  
system resource들이 사용되는 방법을 정의해준다. 웹 브라우저, 게임, 워드프로세서 등이 포함된다.
4. User  
사용자를 의미한다.  

이렇게 크게 총 4가지의 구성요소를 가진다고 볼 수 있다.  
이해를 돕기 위해 그림으로 나타나면 다음과 같다.
 ![image](/img/os.png)
 다시 돌아와서, 운영체제란 무엇인가?? 를 알기 위해 운영체제가 하는 일을 크게 2가지로 정리하면 다음과 같다.
 * __Resource Allocator__
 * __Control Program__  
 
 우선 Resource allocator, 즉 자원을 할당해주는 역할을 한다. 서로 상충되는 request들 사이에서 더 효율적이고 공정한 자원 사용을  
 결정해준다. 그리고 Control program, 즉 에러들을 방지하고, 컴퓨터의 적절하지 않은 사용을 막기 위해 프로그램들의 실행을 관리한다.  
   
 여기까지해서 운영체제를 본격적으로 공부하기 전에 운영체제란 무엇인가에 대해서 알아보았다.  
 사실 운영체제란 무엇인가에 대해서 universally하게 accepted된 정의는 없다. 하지만 운영체제의 목표가 무엇인지, 그리고 무슨 역할을  
 하는지를 알아봄으로써 운영체제에 대해 '아,이런 느낌이구나' 정도의 느낌을 가지고 앞으로 운영체제를 공부해 나가면 훨씬 좋을 것 같다.
