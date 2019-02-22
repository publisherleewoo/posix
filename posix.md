# POSIX CLI

- pwd  
  - print working directory
  - 디렉토리 보여주기
- /
  - root direcory
  - 루트 티렉토리
- cd
  - change directory
  - 디렉토리 바꾸기
- --help
  - simple manual
  - 도움말
- man command
  - manual
  - 도움말
- ls -l
  - list in long format
  - 수정일,생성일 보여주는 리스트
- ls - a
  - show all files
  - 모든 파일 다보여주기
- ls -R  
  - 모든디렉토리 다보여줌
- touch
  - make empty file
  - 빈 파일만들기
- cat hello.txt    
hello world!<br>
이라는걸로 내용을 볼 수 있다.

- .filename
  - hidden file
  - 숨긴 파일 만들기
- mkdir
  - make direcory
  - 디렉토리 만들기
- ./
  - current directory
  - 앞단계 디렉토리
- mv
  - move(rename)
  - 파일명 변경, 파일 이동
  - ex)mv test.txt test2.txt
- rm -r
  - remove directory
  - 디렉토리 제거
- rm 
  - remove file
  - 파일 제거
- nano
  - text editor
  - nano에서 ^는 컨트롤


## ex)
;를 사용하여 연달아 작성할수있다..
```
mkdir dummy;cd dummy;touch hello.txt;cd ..;ls-R
```

##
&&하면 실패하면 성공하곳까지 실행되고, 그후 멈출 수 있다
```
mkdir dummy&&cd dummy&&touch hello.txt&&cd ..&&ls-R
```

