---
title: "Welcome to My blog"
date: 2019-03-28
categories: Studying
---
1. Java 설치
2. 환경변수 설정 ( 시스템변수 -> JAVA_HOME / PATH )
3. cmd 창(window키+r, cmd 타이핑)에서 javac -version, java -version 확인 / set 입력 후 JAVA_HOME, PATH 값 알맞게 들어가 있는지 확인.
4. Hello.java 메모장에 작성.
            class Hello {
            public static void main (String args[]) {
            System.out.println("Hello world");
            }
        }
*  (cmd 명령어)
             https://zetawiki.com/wiki/%EC%9C%88%EB%8F%84%EC%9A%B0_CMD_%EB%AA%85%EB%A0%B9%EC%96%B4_%EB%AA%A9%EB%A1%9D 
5. cmd 창에서 cd(체인지) 로 디렉토리 이동 
cd 주소값
d: (원하는 드라이브 바로 입력)
/ cd .. (뒤로가기)
 c: (원래대로 돌아가기)
/ cd 0* (0으로 시작하는 디렉토리 검색)
 cd 0*p (0으로 시작하고 p로 끝나는 디렉토리 검색)
 cd 0*/1* (0으로 시작하는 디렉토리 -> 내부의 디렉토리 중 1로 시작하는 디렉토리 검색)
6. 컴파일 하기 전에 해당 디렉토리에 컴파일 하려는 파일이 있는지 확인!!
cmd 창에서 dir 로 위치 찾기 (dir/w 가로로 보여줌) 
7. d: 로 이동한 후에 Hello.java 파일이 있는 디렉토리로 이동.
/ javac Hello.java 로 컴파일.
/ javap Hello.class (어떤 바이트코드 파일이 어디서부터 나왔으며, 어떠한 필드와 메소드를 갖고 있는 파일인지를 알려주는 기능, 역컴파일러)
/ type(print) Hello.java
/ java Hello -> 출력




* javac : file not found : Hello.java = 파일을 위치를 못찾는 에러구문.
* Hello.java => Hello.class [java] => JVM 자바버츄얼머신 <=통신= PC(cpu)
* java -verbose Hello (나중에 스레드를 이용하는데 도움되는 개념)
* 컴파일 하면서 클래스파일의 시간, 사이즈 항상 확인해서 컴파일이 맞게 되었는지 체크하기(hotspot과 맞물려 돌아가는지 확인해야하기 때문에)
* System.out.println("Hello JAVA");  - 문장, 문장을 적으면 종결을 해야한다. 
