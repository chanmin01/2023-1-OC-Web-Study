git add는 작업 디렉토리(working directory)상의 변경 내용을 스테이징 영역(staging area)에 추가하기 위해 사용하는 Git 명령어다. 파일과 폴더를 모두 arguments로 받는다. 또한 git add는 Untracked상태의 파일을 Tracked상태롤 바꿀때와 not staged상태의 파일을 staged상태로 바꾸어줄때 사용하며 Merge한 파일중 충돌난 상태의 파일을 Resolve상태로 만들때 또한 사용한다.
git add 명령어는 사용자가 커밋을 하기 전까지 변경된 내용들을 모아놓기 위해 사용한다. 따라서 git commit이라는 명령어를 사용하기 이전에는 아무리 git add 명령어를 실행해도 Git 저장소의 변경 이력에는 어떤 영향도 주지 않는다. git add는 스테이징 영역에만 올릴뿐 Git 저장소에 실질적인 영향을 못미치기 때문이다. 실질적인 영향을 미치는 명령어는 git commit이 된다.

push 명령어는 로컬 저장소에서 commit된 파일을 업로드해준다. 따로 저장할 브랜치를 지정할 수 있으며, 보통 origin브랜치를 주로 사용한다.


git pull: git remote 명령을 통해 서로 연결된 원격 저장소의 최신 내용을 로컬 저장소로 가져오면서 병합한다. git push의 반대 성격이라 생각하면 된다.
git fetch: 로컬 저장소와 원격 저장소의 변경 사항이 다를 때 이를 비교 대조하고 git merge 명령어와 함께 최신 데이터를 반영하거나 충돌 문제 등을 해결한다.
