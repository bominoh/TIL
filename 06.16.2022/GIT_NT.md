- `git config --global user.name <user_name>`: username
- `git config --global user.email  <email>'`: email
  - config는 내 로컬과 

- `git init`: 레포를 만들고 워킹 디렉토리랑 연결시켜줄 때 최초 1회

-> 레포를 만들때마다 계속 해야한다.

- `git status`: 워킹 디렉토리에 어떤 변화가 있는지 알아보는 명령어. 
  - 워킹 디렉토리 단계와 스테이징 에리아 단계의 변화

- `git add` + `.` : 전체 다 staging area로 올리기

- 햣`git add` + `파일명.확장자`: 이것만 올려
  -  `git add`파일1 파일2 파일3

- `git commit` + `-m` `"commit message"`: 

  - 명령어로 적기

  - 동사형으로 시작하기
  - 영어로 적기  
  -  약속일뿐 법은 아니다

-  `git log --oneline`: `-`하이폰 두개

  - `commit` 된 상황에서 어떤 메세지로 언제 뭐가 올라갔는지 알기위한 명령어

- `git remote add` + `origin <github 주소>`: 내 워킹 디렉토리와 레포지토리 연결

- `git remote -v`: 리코트가 잘 들어

- `git push` + `origin master` : 최종으로 깃헙에 올린다.



<hd>

`git branch` : 브랜치의 종류, 어느 브랜치인지 확인하기

`git branch <브랜치>`  : 브랜치 생성

- 브랜치 생성 예시 `git branch sunny` 
- 이미 있는 브랜치 명을 작성햇을 땐 에러 발생
  - `git checkout	< 브랜치명>` : 브랜치 이동
  - 
  - 