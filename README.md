# HICC_git_basic 

git은 파일들을 시간별로 쉽게 저장하고 가져오고 합칠 수있는 유용한 툴이다.

git의 사용방법으로는 terminal을 사용하는 방법과 GUI(Source tree)를 사용하는 방법이 있다.

다음의 내용들은 vscode의 terminal을 사용하는 것을 기준으로 한다.

우선 vscode에서 shift + o 로 git으로 관리하고자 하는 폴더를 열어준다.

command + shift + . - 숨겨진 폴더를 볼 수 있게해준다. (.git 파일은 숨겨져있음)

git init - 폴더를 깃으로 관리를 시작한다.

git config --global user.name "이름" - 폴더 생성자의 이름을 등록한다.

git config --global user.email "메일주소" - 폴더 생성자의 메일주소를 등록한다.

git status - 폴더에 어떠한 파일들이 깃으로 관리되고 있는지 상태를 확인한다.

git add -A - 폴더의 모든 파일을 git으로 관리한다.

git commit -m "~" - 커밋에 대한 설명(이름)을 작성한다.

git log - 커밋한 내용들을 보여준다.

; + q - 터미널에서 입력이 안될때 빠져나오는 vi 명령어이다.

git reset ~ --hard - ~시점으로 폴더를 되돌린다.

git revert ~ - 지금 시점의 폴더를 저장한 상태로 ~시점으로 되돌린다.

; + wq - 원래상태로 저장하겠다는 vi 명령어이다.

git branch ~ - 명령의 실행시점의 branch의 상태를 그대로 가져와 ~이름의 branch를 새롭게 분기한다.

git checkout ~ - ~이름의 branch로 이동한다.

git merge ~ - merge를 받을 branch에서 merge할 branch를 입력한다.

git branch -D ~ - ~이름의 branch를 삭제한다.

git log --graph --all --decorate - 시각화된 branch 작업내용을 볼 수 있다.