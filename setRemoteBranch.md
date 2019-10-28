# git Clone 하고 master Branch만 나올때

#### 처음 clone를 이용해서 local repository를 만들때 default브런치 이외에는 생성 되지 않는다. 그러므로 커맨드를 이용해서 원격 branch를 가져올 필요가 있다. 

## 원격 branch의 상태 갱신
```bash
git remote update
```

> 원격의 branch를 찾지 못해서 발생하는 `fatal: Cannot update paths and switch to branch 'feature/rename' at the same time.`를 해결해줌

## remote의 branch를 체크

```bash
git branch -r
```

> `git branch -r` 는 원격에 있는 브런치리스트를 보여주고 `git branch -a` 경우 원격, 로컬의 브런치 전부 보여준다. 

## remote로부터 branch가져오기

> `git checkout -t [가져올remote브런치명]`-t는 리모트 브런치명 그대로 로컬에 브런치를 생성하여 리모트 브런치 내용을 가져온다.