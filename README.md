# 제목1

## 제목2

### 제목3

#### 제목4

##### 제목5

###### 제목6

1. 순서가 있는 목록
2. 순서가 있는 목록

   1. 순서가 있는 서브 목록
   2. 순서가 있는 서브 목록

- 순서가 없는 목록

  - 대쉬(hyphen)

  * 별표(asteriks)

  - 더하기(plus sign)

### 링크 (Links)

[구글](https://www.google.com/)  
[네이버](https://www.naver.com)  
[구글홈페이지]<https://www.google.com/>
[네이버홈페이지]<https://www.naver.com/>

### 이미지 (images)

![무지개고양이](https://cdn.aitimes.kr/news/photo/202303/27617_41603_044.jpg)

[![google](https://as2.ftcdn.net/v2/jpg/05/56/64/63/1000_F_556646398_8IJsoryuJUH8KTM3MI7ZuBxQOuXY5603.jpg)](https://www.google.com)

![우주고양이](https://i.etsystatic.com/30429057/r/il/ff7ada/4630539197/il_fullxfull.4630539197_gdbg.jpg)

### 인라인(inline)코드 강조

`백틱1개`는 `인라인 코드 강조`를 의미한다.

### 블록(block)코드 강조

`을 세번 하면 <pre \>의미이고 html을 하면 <code \>을 의미한다.

```html
<a href="https://www.naver.com/">네이버</a>
```

```java
  public class Exam{
     public static void main(String[] args){
        System.out.println("exam");
     }
  }
```

### 표(table)

| 이름   | 성별 | 주소          |
| ------ | :--: | ------------- |
| 홍길동 |  남  | 경기도 화성시 |
| 김민재 |  남  | 서울 서초구   |

### 인용문(blockQuote)

> 타인의 말이나 문장을 직접 또는 간접으로 가져옵니다.
>
> > 인용문1
> >
> > > 인용문2

### 수평선(Horizontal Rule)

## 각 기호를 3개 이상 입력하면 된다.

(Hyphens)

---

(Asteriks)

---

(Underscores)

### 줄바꿈 (line breaks)

바다<br>
하늘<!--띄어쓰기 2번 이상-->  
구름

# TIL

## 리눅스 명령어

1. ls

   > list(목록)

2. cd
   change directory (작업 경로 변경)

3. rm
   remove (파일 삭제)

4. mkdir  
   make directory(작업목록 생성)

5. rmdir  
   remove directory(작업목록 삭제)

6. touch  
   파일생성

7. cat
   파일의 내용 출력

## Git

1. init  
   git 생성
2. add <파일명>  
   staging area로 이동
3. commit -m <메세지>  
   Repository로 이동
4. push <원격저장소><브랜치>  
   원격(GitHub)으로 이동
5. pull <원격저장소><브랜치>  
   원격에서 로컬로 복사
6. clone <원격저장소><브랜치>  
   원격에서 로컬로 복제

7. status  
   Staging Area의 상태
8. log  
   repository의 상태

9. git commit --amend  
   바로 전commit과 Staging Area의 Merge을 할때
10. git restore --staged <파일명>
    Staging Area의 파일을 Working Directory로 가져옴

![Git Sheat Sheet](https://i.redd.it/8341g68g1v7y.png)
![Git Cheat Sheet](https://intellipaat.com/mediaFiles/2019/03/Git-Cheat-Sheet.jpg)
