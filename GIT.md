# GIT



바탕화면 우클릭 - Git Bash Here 

git 계정 확인

```bash
git config --global -l
```



```bash
git add a.txt b.txt   # 복수의 디렉토리
git add test_folder/  # 특정 폴더
git add c.txt         # 특정 파일
git add "*.txt"       # 특정 확장자
```



git과 github은 다른 개념. 

gitlab, github등 git을 사용하기 위한 다양한 서비스 사이트가 있음.



붙여넣기 : shift+insert

## 원격저장소 조회

```bash
git remote -v   #verbose
origin  https://github.com/YeonjuKim1/test.git (fetch)
origin  https://github.com/YeonjuKim1/test.git (push)
```





## 원격저장소 추가

```bash
git remote add <원격저장소이름> <주소>
git remote add origin https://github.com/<username>/<저장소이름>.git
```

- git아, 원격 저장소(`remote`)를 추가해줘(`add`). `origine` 이라는 `이름`으로, `주소`를
- 원격저장소가 이미 설정된 경우 설정이 되지 않는다.(remote origin already exists)



## 원격저장소 push

```bash
git push <원격저장소이름> <브랜치이름>
git push origin master
```

- git, push, origin에 master 브랜치를!!
- `-u` 옵션: upstream 옵션
  - `git push` 라고 명령을 하더라도 설정된 원격저장소에 브랜치를 push
  - `git push -u origin master`
  - 