Git 기초#

- .git 폴더는 무엇인가요?
->  커밋이 담겨져있는 폴더
- .git 폴더를 만드는 방법은?
-> git init

Project 폴더 -> 내가 작업할 최상위 폴더(root directory)

git 도움을 주는 확장앱 설치
-> Git Graph

-1 gitignore -> git init 하면 .git 폴더 생성
->내가 굳이 올릴필요가 없는 파일혹은 디렉토리 (아이디 패스워드를 저장하는 text 파일,node modules,package-lock.json 등등)을
관리안하게 할수있다.
사용방법 ->
프로젝트 폴더에서 
.gitignore파일을 생성해주세요
그 파일은 한줄한줄 읽히는데
적혀있는 폴더나 파일은 추적하지않습니다.

-2 Reset, Revert 커밋을 뒤로 돌아가는 행위

-3 branch  커밋을 나누는 행위

-4 merge, rebase 커밋을 합쳐주는 행위

-5 git log 명령어 
-> 커밋했던 히스토리를 볼수있다.

-6 git rm -r [파일명] : 로컬과 원격저장소를 다 지움
    git rm --cached -r [파일명] : 원격저장소에서만 지움