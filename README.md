# Avoid_Virus_Game

## 1. 개요

시스템 프로그래밍 5팀의 프로젝트입니다.   
수업을 통해 배웠던 리눅스의 개념들을 활용하여   
바이러스를 피하는 콘솔 게임을 제작하였습니다.

## 2. 컴파일
```
$ cc main.c -lncurses -o main
```
## 3. 게임화면 & 게임방법

 * 게임화면은 총 3개로 구성되어있고, 키보드 방향키 <- , -> 를 활용하여 플레이어를 좌우로 움직여 바이러스를 피하면 됩니다.

### 1. 타이틀

![title](https://user-images.githubusercontent.com/33113480/102457938-dcd9f900-4086-11eb-8076-a69054997cf4.JPG)
 
 * 타이틀의 모습입니다. 아무키나 입력시 게임이 진행됩니다.

****************************

### 2. 게임시작

![main](https://user-images.githubusercontent.com/33113480/102457993-f11df600-4086-11eb-8092-84e7508255ba.JPG)

- 게임이 시작된 모습입니다. 키보드 방향키를 사용하여 플레이어를 좌우로 움직일 수 있습니다.

*****************************

### 3. 게임오버

![gameover](https://user-images.githubusercontent.com/33113480/102458017-f8450400-4086-11eb-8223-a0f00e6c8fe7.JPG)

- 플레이어가 바이러스와 닿으면 Game Over 메세지가 나오며 게임이 종료됩니다.

