## git 기본 명령어
### git init
이후 `(master)` 뜬다!

### git add
working dir에서 작업 완료된 파일을 staging area 위로 올린다.
```
git add 파일명
```

### git commit
메시지(-m) 남기기
>why? 버전 관리 프로그램 git이 변경사항에 대한 <육하원칙>을 작성하기 위해 왜 수정했는지 정보가 필요해서

### git status
파일 상태를 알려줌(Untracked , Modified , New File , nothing to commit ...)

### git log
변경사항들의 기록을 보고 싶을 때
```
git log --oneline
```
===>로컬 저장소(내컴퓨터)에서 버전 관리할 때

## Github
원격에서 나의 변경 사항 기록들을 가지도록 사용할 수 있다!
### repository
우측 상단 `+`버튼 눌러서 만들어용
URL이 생성된다 --> 이것이 원격 저장소의 주소
### 현재 나의 로컬 저장소와 연결하기
```
# 원격 저장소 연결
git remote add original(<--내가 설정but이 단어로 쓰자) URL
#연결 확인
git remote -v
```
### 로컬 저장소에서 변경 사항을 원격 저장소로 보내기 
```
git push original master
#master = branch를 의미한대
```

