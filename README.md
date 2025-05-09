**sass --watch scss/style/scss css/style.css**   

## 깃 초기화와 커밋   
1. 깃 초기화 git init   
2. 깃 상태 git status   
3. 깃에 모든것을 올리기 git add .   
4. > 깃에 로컬 작업저장소 등록하기 git config --global user.name 아이디    
   > git config --global user.email 이메일   
   > git remote add origin 내 깃허브 프로젝트 저장소 주소   
   > _--> git폴더에 config 파일안에 [remote "origin"] 부분에서 확인가능_   
5. 커밋하기 git commit -m "커밋내용또는이름"   
6. 커밋 로그 git log      

_(만약 프롬프트? 명령어입력하는 커서 가 사라졌다면 q 누르면 생김)_   
_(터미널이 너무 지저분하다면 명령서 clear 입력)_

7. 원하는시점으로 되돌리기 git checkout 커밋아이디     
8. 마지막시점으로 되돌리기 git checkout master    

## 깃 브랜치 생성과 브랜치 푸쉬   
1. 브랜치 생성 git branch 원하는브랜치명   
2. 브랜치 생성결과(현재 브랜치위치) git branch -v    
3. 생성한 브랜치로 이동 git checkout 생성한브랜치명   
4. master 브랜치로 이동 git checkout master   
5. 내 깃 저장소에 브랜치 올리기 git push origin 브랜치명 또는 git push master 또는 git push origin --all

## 깃 머지하기 
1. 우선 pull하기 git pull origin master
2. 머지 할 파일 확인하기 git status
   > 만약 (use "git commit" to conclude merge) 가 나온다면
   > 충돌은 이미 해결했고, Git이 머지를 마무리하는 커밋만 해주면 됨 git commit
   >> 이때만약 커서가 사라졌다면 :wq 입력 (명령모드진입 + 저장 후 종료) -> :q 입
3. 손으로 충돌부분 수정(<<<<<<<, =======, >>>>>>>) 괄호 속 문자가 지워지게
4. 수정후 git add .
5. 커밋 git commit -m "커밋메시지"
6. 다시푸시 git push origin master

## 머지 포기하기
1. git merge --abort

## 깃 원격저장소를 내 로컬에 복사하기   
1. 깃 원격저장소를 내 로컬에 복사하기 git clone 복사한 깃허브 주소   
_-->master 브랜치만 활성화 됨_   
2. 모든 브랜치보기 git branch -a   
3. 원하는 브랜치 이동 git checkout origin/브랜치명   
4. git branch 브랜치명   
5. git branch -v   
6. git checkout 브랜치명    
7. git branch -v     
