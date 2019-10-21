# Commit순서

![순서도](https://git-scm.com/figures/18333fig0201-tn.png)

* Tracked(관리대상): 이미 스냅샷에 포함이 되어있는 파일
* UnTracked(비관리대상):워킹 디렉토리에 있으나 한번도 commit가 되지 않은 파일 ex:새로운 파일 혹은 gitignore대상 파일
* Unmodified(수정되지 않음):원격 저장소에서 clone을 하고나면 모든 파일이 이상태이다. 
* Modified(파일이 수정된 상태):현재 브런치 상태에서 파일을 수정할경우
* Staged(commit를하면 저장소에 기롤되기 직전): Commit을 할때 수정상태가 저장 되는 파일들

## command
 * `git status ` : 저장소 상태 확인
 * `git add <file>` : commit할때 수정상태를 저장할 파일 올리기
 * `git commit -m "수정사항"`: Commit 



출처 - [Git의-기초-수정하고-저장소에-저장하기](https://git-scm.com/book/ko/v1/Git%EC%9D%98-%EA%B8%B0%EC%B4%88-%EC%88%98%EC%A0%95%ED%95%98%EA%B3%A0-%EC%A0%80%EC%9E%A5%EC%86%8C%EC%97%90-%EC%A0%80%EC%9E%A5%ED%95%98%EA%B8%B0)