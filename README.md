*sass --watch scss/style/scss css/style.css
*깃 초기화 git init
깃 상태 git status
깃에 모든것을 올리기 git add .
깃에 로컬 작업저장소 등록하기 git config --global user.name 아이디 
   git config --global user.email 이메일
   git remote add origin 내 깃허브 프로젝트 저장소 주소
--> git폴더에 config 파일안에 [remote "origin"] 부분에서 확인가능
커밋하기 git commit -m "커밋내용또는이름"
커밋 로그 git log

(만약 프롬프트? 명령어입력하는 커서 가 사라졌다면 q 누르면 생김)
(터미널이 너무 지저분하다면 명령서 clear 입력)

원하는시점으로 되돌리기 git checkout 커밋아이디  
마지막시점으로 되돌리기 git checkout master 

브랜치 생성 git branch 원하는브랜치명
브랜치 생성결과(현재 브랜치위치) git branch -v 
생성한 브랜치로 이동 git checkout 생성한브랜치명
master 브랜치로 이동 git checkout master

내 깃 저장소에 브랜치 올리기 git push origin 브랜치명 또는 git push master 또는 git push origin --all
깃 원격저장소를 내 로컬에 복사하기 git clone 복사한 깃허브 주소
-->master 브랜치만 활성화 됨 
모든 브랜치보기 git branch -a
원하는 브랜치 이동 git checkout origin/브랜치명
git branch 브랜치명
git branch -v
git checkout 브랜치명
git branch -v  
