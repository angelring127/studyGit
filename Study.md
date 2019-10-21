# Git 용어 정리

## Respository
##### 말 그대로 파일 및 폴더를 저장하는 저장소 줄여서 repo라고 말한다.

### 종류
1. Remote Respository(원격 저장소)

	* gitHub, gitlab같은 전용 서버에 파일 및 폴더를 저장 하며 관리된다.  여러 사람들과 함께 공유 하는 곳
	* 주로 프로젝트 별로 respository를 만든다.
	* 사람들이 서버에있는 원격저장소를 공유해서 공동작업을 할 수 있습니다.
2. Local Repository(로컬 저장소)
	* 개인 PC에 프로젝트(파일 및 폴더) 저장 되는 개인 저장소 
	* 저장소라고 일컬어지고 있습니다.
	* 저장소를 만드는 방법은 로컬에 새로운 저장소를 만들거나 혹은 원격 저장소를 로컬 저장소로 복사? 로컬을 만들고 거기다 복사?

	
## Commit
##### 변경을 기록한다. 마치 스냅샷을 찍듯 작업소의 상태를 복사해서 저장소에 보존
	git commit -m "commit을 할 내용"


## Push
##### 로컬 저장소의 자료를 원격 저장소에 올리는 행위 
	git push origin master

- 권한으로인한 푸쉬가 되지 않는경우 맥의 경우 키체인에서  깃등록 정보를 삭제 혹은 수정

## Branch

##### 가지를 친다고 한다. 
![Branch Screenshot](https://rogerdudler.github.io/git-guide/img/branches.png)

## CheckSum
#####git에서 사용하는 가장 기본적인(Atomic)데이터 단위이자 git의 기본 철학이라고 한다. 

* CheckSum은 SHA-1해시를 이용해서 만들어진다.  
* CheckSum을 이용해서 식별한다.



출처 - 
[깃 간편 설명서](https://rogerdudler.github.io/git-guide/index.ko.html)