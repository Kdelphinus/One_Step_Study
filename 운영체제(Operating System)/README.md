# 운영체제(Operating System)

## 개요
- 기간: 2023.01.16 ~ 2023.02.18(6주 과정)
- 교재: [Operating Systems: Three Easy Pieces](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/bd597fb0-9881-4080-a55c-ec98034831a2/Operating_Systems_Three_Easy_Pieces.pdf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20230116%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20230116T105552Z&X-Amz-Expires=86400&X-Amz-Signature=65ed8245ef1893f313661b69480a54f4f1a79e2c82a5a7771a87b2f2c5df4dfa&X-Amz-SignedHeaders=host&response-content-disposition=filename%3D%22Operating%2520Systems%2520Three%2520Easy%2520Pieces.pdf%22&x-id=GetObject)
- 저자: Remzi Arpaci-Dusseau, Andrea Arpaci-Dusseau
- 자료: [강의 링크](https://pdos.csail.mit.edu/6.828/2016/xv6.html)

## 과제
- 과제: [Homework](https://pages.cs.wisc.edu/~remzi/OSTEP/Homework/homework.html)
- 과제 github: [Homework github](https://github.com/remzi-arpacidusseau/ostep-homework/)

## 규칙
- 매주 월 ~ 토요일까지 해당 주차의 내용 공부
- 매일 공부한 내용을 "공부 과정 공유"에 올리기
- 매주 토요일에 다른 스터디원이 공부한 내용을 보고 코멘크 달기

## 교재 서론
- [역자 서문](https://pages.cs.wisc.edu/~remzi/OSTEP/Korean/00-preface-tx.pdf)
- [서문](https://pages.cs.wisc.edu/~remzi/OSTEP/Korean/00-preface.pdf)
- [이 책에 관한 대화](https://pages.cs.wisc.edu/~remzi/OSTEP/Korean/01-dialogue-threeeasy.pdf)

## Index
- [Introduction to OS](https://pages.cs.wisc.edu/~remzi/OSTEP/Korean/02-intro.pdf)
- Part1. Virtualization
  - [1. CPU Virtualization](https://pages.cs.wisc.edu/~remzi/OSTEP/Korean/03-dialogue-virtualization.pdf)
    - [The Abstraction: The Process](https://pages.cs.wisc.edu/~remzi/OSTEP/Korean/04-cpu-intro.pdf)
    - [Interlude: Process API](https://pages.cs.wisc.edu/~remzi/OSTEP/Korean/05-cpu-api.pdf)
    - [Mechanism: Limited Direct Execution](https://pages.cs.wisc.edu/~remzi/OSTEP/Korean/06-cpu-mechanisms.pdf)
    - [Scheduling: Introduction](https://pages.cs.wisc.edu/~remzi/OSTEP/Korean/07-cpu-sched.pdf)
    - [Scheduling: The Multi-Level Feedback Queue](https://pages.cs.wisc.edu/~remzi/OSTEP/Korean/08-cpu-sched-mlfq.pdf)
    - [Scheduling: Proportional Share(Lottery & Stride Scheduling)](https://pages.cs.wisc.edu/~remzi/OSTEP/Korean/09-cpu-sched-lottery.pdf)
    - [Scheduling: Multiprocessor Scheduling (Advanced)](https://pages.cs.wisc.edu/~remzi/OSTEP/Korean/10-cpu-sched-multi.pdf)
    - [Summary on CPU Virtualization](https://pages.cs.wisc.edu/~remzi/OSTEP/Korean/11-cpu-dialogue.pdf)
