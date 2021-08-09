# GIT



폴더 우클릭 - Git Bash Here 

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



## 기본 명령어

```bash
git init
git add .
git commit -m "메시지"
git remote add origin <주소>
git push origin master
```



1. 목록1
   1. tab하면 하위 목록
   2. 엔터하면 계속됩니다.
2. shift+tab해주시면 상위 목록이 됩니다.

```bash
```

## 알고리즘 문제

- https://www.acmicpc.net/problem/2557

- https://www.acmicpc.net/problem/1000
- https://programmers.co.kr/learn/courses/30/lessons/12932
- https://swexpertacademy.com/main/main.do
