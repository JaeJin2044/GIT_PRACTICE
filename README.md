# git 기본 명령어 정리 

## Root Folder연결 하는 Command
- git init(깃 생성)
- git remote add origin (repostiory address)  
(원격 저장소의 주소와 로컬 폴더를 연결)



<br />

## pull 
**push전에pull이있다고 기억!!** <br />
- git pull origin '해당브랜치명'

<br />


## push
- git status(현재 로컬폴더와 git과의 싱크확인)  
- git add .(로컬 폴더와 깃 repostiory들을 모두 Tracking)
- git commit -m "message"(인식 할 수 있는 코멘트를 작성)
- git push origin master(실제로 깃을 push)

<br />

## branch
- git branch(브랜치 목록)
- git branch '브랜치명'  (브랜치 생성)
- git branch -d '브랜치명 (해당 브랜치 삭제)

<br />

## checkout
- git checkout -b '브랜치명' (브랜치를 생성하면서 이동)
- git checkout '브랜치명' (브랜치를 생성)

<br />

## reset
#### 버전 되돌리기
- git reset --hard HEAD~1  (현재 최신버전에서 1버전 되돌리기)
- git reset --hard HEAD~2 (2단계 이전 버전으로 되돌리기)

#### 명령 취소 하고 다시 원상태로 되돌리기 
- git reset --hard ORIG_HEAD

<br />

## etc
- git remote -v (현재 나의 repositroy url주소 확인)




