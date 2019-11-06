# 20191106 History 정리

## 내가 관리자인 경우 

> ```bash
> rm -rf .git
> // git 내역 삭제
> 
> git init
> git add .
> // 깃 초기화 후 모든 파일 Staging상태로 전환
> 
> git commit -m "inital commit"
> // commit
> 
> git remote add origin [remote repository url]
> // 리모트 레포 추가
> 
> git push -u --force origin master
> // 강제로 푸쉬
> ```
>
> 내가 관리자인경우 상관 없으나 꽤나 위험성을 내포한 작업이므로 되도록이면 하지 말자 



## 일반적인 history 정리

1. 작업을한 브런치(workBranch) 이외 브런치의 시작점에 새로운 브런치(newBranch)를 작성
2. workBranch를 newBranch에 merge한다.
3. 시작점에서 interactive rebase
4. squash작업을 한다.
5. Commit 내용 정리하고 Interactive rebase 를 수행한다.