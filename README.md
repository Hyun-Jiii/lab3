# lab3

1. 자신의 github 저장소에 lab3 프로젝트를 생성하고 아래의 모든 과제 프로그램을 업로드한다.

2. 파일 및 디렉토리와 관련된 함수들을 사용하여 프로그램을 작성하여 실행하여보고, 익숙해지도록 사용해 본다.
 
3. 주어진 디렉토리 내에 존재하는 파일과 디렉토리를 나열하고, 디렉토리의 경우 재귀적으로 방문해서 그 디렉토리 내에 존재하는 파일과 디렉토리를 나열하는 프로그램을 작성하시오.(ls -R 명령과 동일한 결과를 보이도록)
 
4. 몇 개의 문장을 타자시 잘못 타이핑한 횟수와 평균 분당 타자수를 측정하는 타자 연습 프로그램을 구현하시오.
 
5. 프로세스와 관련된 함수들을 사용하여 프로그램을 작성하고 실행하여 보고, 익숙해지도록 사용해 본다.
 
6. system 함수는 쉘 명령이 실행되도록 하는데, 예를 들면, system("ls -la")을 호출하면, 현재 디렉토리의 파일들을 나열해 준다. 이와 같은 기능을 수행하는 함수를 직접 구현하여 보자. 또, 이 함수를 이용하는 예제 프로그램을 통해서 "a.out ls -la"와 같이 명령이 잘 작동하도록 해 보자.
 
7. 시그널과 관련된 함수들을 사용하여 프로그램을 작성하고 실행하여 보고, 익숙해지도록 사용해 본다.
 
8. 프로세스 간 통신 함수들을 사용하여 프로그램을 작성하고 실행하여 보고, 익숙해지도록 사용해 본다.
 
9. 메시지 큐를 사용하여 텍스트 기반의 간단한 채팅 프로그램을 구현하시오.
 
10. 공유 메모리를 사용하여 한 파일을 다른 파일로 복사하는 프로그램을 작성하시오. 단, 부모(읽는 프로세스)와 자식(쓰는 프로세스)프로세스가 공유 메모리 영역을 동시에 접근하는 일이 없도록 세마포어 같은 동기화 기법을 활용하시오.
 
11. 간단한 쉘 프로그램을 만들고 다음과 같이 동작하도록 수정하시오.(팀프로젝트)

 A. "exit"를 치면 프로그램을 끝내도록 프로그램을 수정하시오.
 B. csh, bash 등에서처럼 쉘 명령의 마지막에 '&'을 입력하면 백그라운드로 실행되도록 프로그램을 수정하시오.
 C. csh,bash 등에서처럼 인터럽트키 (SIGINT: Ctrl-C, SIGQUIT: Ctrl-Z)가 동작하도록 프로그램을 수정하시오.
 D. 파일 재지향 (>, <) 및 파이프(|) 기능이 가능하도록 프로그램을 수정하시오.
 E. ls, pwd, cd, mkdir, rmdir, ln, cp, rm, mv, cat 명령을 팀원이 공평하게 나누어 구현하시오.
