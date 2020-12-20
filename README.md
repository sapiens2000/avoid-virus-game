# Avoid Virus Game

## 1. 개요

시스템 프로그래밍 5팀의 프로젝트입니다.   
수업을 통해 배웠던 리눅스의 개념들을 활용하여   
바이러스를 피하는 콘솔 게임을 제작하였습니다.

## 2. 컴파일
```
$ cc main.c -lncurses -o main
```
## 3. 게임방법 & 게임화면

 * 키보드 방향키 <- , -> 를 활용하여 플레이어를 좌우로 움직여 바이러스를 피하는 게임입니다. Shift 키를 함께 누르고 이동하면 더 빠르게 이동할 수 있습니다. 키보드 F1를 누르면 게임을 강제 종료 시킵니다.
 * 게임 화면은 시작 화면, 게임 화면, 종료 화면으로 총 3개로 구성되어있습니다.

### 1. 시작 화면

![title](https://user-images.githubusercontent.com/33932392/102474713-4dd7db80-409c-11eb-95e0-b9389af09b08.png)
 
 * 타이틀의 모습입니다. 아무키나 입력시 게임이 진행됩니다.

****************************

### 2. 게임 화면

![main](https://user-images.githubusercontent.com/33932392/102474896-8d9ec300-409c-11eb-9984-3e662d615562.png)

- 게임이 시작된 모습입니다. 키보드 방향키를 사용하여 플레이어를 좌우로 움직일 수 있습니다.

- 하단의 SCORE는 플레이어의 점수로, 피하는데 성공한 바이러스의 개수를 나타냅니다.

*****************************

### 3. 종료 화면

![gameover](https://user-images.githubusercontent.com/33932392/102475093-c8a0f680-409c-11eb-80a6-132531536194.png)

- 플레이어가 바이러스와 닿게되면 게임을 종료합니다.

- GAME OVER 메세지와 획득한 점수를 출력합니다.

### 4. 발표 / 데모 동영상

[![발표](https://i9.ytimg.com/vi/uwiNG2lNnN0/mq1.jpg?sqp=CJyk-_4F&rs=AOn4CLAfq39XkNST_Z3JXjiJKMJhwi_sPw)](https://youtu.be/uwiNG2lNnN0)
