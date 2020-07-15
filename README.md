# linux_tutorial
리눅스 설치부터 실행까지 기초 과정 튜토리얼

# 필요한 개념
 - [운영체제](#운영체제)
 - [커널](#커널)
 - [쉘](#쉘)

<!-- 운영체제 -->
# 운영체제
## 운영체제란? (Operating system = OS)
An operating system (OS) is system software that manages computer hardware, software resources, and provides common services for computer programs.  
: 운영체제란 컴퓨터 하드웨어, 소프트웨어를 관리하고, 컴퓨터 프로그램을 사용하기 위해 공통된 서비스를 제공하는 시스템 소프트 웨어이다.  

<p align="center">
  <img src ="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e1/Operating_system_placement.svg/250px-Operating_system_placement.svg.png">
  <img src ="https://upload.wikimedia.org/wikipedia/commons/a/a3/Operating_system_placement_kor.png">
</p>
                                                                                                                             
<!-- 커널 -->
# 커널
## 커널이란? (Kernel)
The kernel is a computer program at the core of a computer's operating system with complete control over everything in the system.  
: 커널(kernel)은 컴퓨터의 운영 체제의 핵심이 되는 컴퓨터 프로그램의 하나로, 시스템의 모든 것을 완전히 통제한다.

<p align ="center">
 <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/8f/Kernel_Layout.svg/220px-Kernel_Layout.svg.png">
</p>

- 운영 체제의 다른 부분 및 응용 프로그램 수행에 필요한 여러 가지 서비스를 제공한다. 핵심(核心)이라고도 한다.
- 커널의 역할: 보안, 자원 관리, 추상화
  - 컴퓨터 하드웨어의 보안을 책임진다. (보안)
  - 한정된 시스템 자원을 효율적으로 관리하여 프로그램의 실행을 원활하게 한다. (자원 관리)  
    +) 스케줄링 : 프로세스 처리기를 할당함
  - 하드웨어는 같은 종류의 부품으로 다양하게 설계할 수 있기 때문에 하드웨어에 직접 접근하는 것은 문제를 매우 복잡하게 만들 수 있다.  
   -> 커널은 깔끔하고 일관성 있는 인터페이스를 하드웨어에 제공하기 위해 몇 가지 하드웨어 추상화들로 구현된다. (추상화)  
    +) 하드웨어 추상화 : 같은 종류의 장비에 대한 공통 명령어의 집합
 
<!-- 쉘 -->
# 쉘
## 쉘(Shell)과 커맨드(commands)
> commands are just text you type in the terminal
- 커맨드는 터미널에서 입력한 문자일 뿐이다.

> commands are interpreted by the shell  
- 커맨드는 쉘에 의해 번역된다

> Different shells can interpret the same text in different ways.  
- 쉘은 다양한 형태의 쉘이 있으며 같은 글자를 다른 방식으로 해석한다.  
 ex) gift를 입력 -> (쉘이 영어로 해석) -> '선물'이라는 뜻이 나옴
     gift를 입력 -> (쉘이 독일어로 해석) -> '독'이라는 뜻이 나옴  
     
> The terminal is the window to the shell.  
- 터미널은 쉘과 이어주는 중간 역할을 한다. +) 터미널 없이 커맨드 입력을 못함.

> +) Commands are case-sensitive.  
- +) 커맨드는 대/소문자를 고려해야한다. 그렇지 않으면 에러가 발생할 수 있다.

-대부분 리눅스,우분투는 bash shell을 사용한다


# 설치 
 
1. Virtual box 설치 ([virtualbox](https://www.virtualbox.org/wiki/Downloads))
 - virtual box란?  
  : 현재 내 컴퓨터에 영향을 끼치지 않는 새로운 컴퓨터 공간

2. Ubuntu(우분투) 설치 ([Ubuntu](https://ubuntu.com/download/desktop))
 - 작성 기준 최신 빌드 : Ubuntu 20.04 LTS
 

# 핵심 내용
- Linux Commands
 > Commands = CommandName -options inputs  
  - ex) cal -A 1 12 2017 --> -A는 after, 즉 1달후에 캘린더 보여줌  
     cal -B은 Back, 전의 달을 보여줌  
- CommandNames need to be on the shell's search path.  
ex) echo $PATH: 경로찾기
- Commands operate on inputs
- Options modify a commands's behaviour
- Some Commands can have long form and short form options.
- Shrot form options have one dash(-) and Long form options have two dashes(--)  
ex) long form options으로는 --after, --before


 
 # Etc
 * 리눅스 베스트 강좌 리스트  
   - [9 Best Linux Course, Certification, Training and Tutorial Online [2020 UPDATED]](https://digitaldefynd.com/best-linux-tutorial-certification-training-course/)
   - [Udemy) 리눅스 베스트 강좌](https://digitaldefynd.com/best-linux-tutorial-certification-training-course/)
 * [리눅스 기초 문서](https://ruinick.tistory.com/203)
 * [한국 우분투 커뮤니티](https://www.ubuntu-kr.org/)


# Reference
- wiki 
- 운영체제란 무엇인가? : https://coding-factory.tistory.com/300
