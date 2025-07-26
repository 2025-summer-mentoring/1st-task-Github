# Git 과 Github 를 Markdown 문법으로 정리하기!
- 기한 7월 27일 11시 59분까지
- 궁금하거나 모르는거 있으면 언제나 질문하기!

***Git*** 이란 로컬에서 사용하는 버전 관리 시스템이고 로컬저장소입니다. 
*대표 문법으로는 init, add, commit, pull, clone, merge 등이 있습니다.*
Git의 동작 과정으로는 작업디렉토리(Working Directory) -> 스테이징 영역(Staging Area) -> 로컬저장소(Local Repository)가 있습니다.

***GitHub*** 란 Git저장소를 인터넷에 올릴 수 있는 서비스이고 원격저장소입니다. 여러 사람과 협업 할 때 유용합니다.
###### 협업을 위한 기능으로는 Pull Requests, Issues 등이 있습니다. ######
GitHub의 동작 과정으로는 Push -> Issues -> Pull Requests -> Merge가 있습니다.

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - 

#### 다른 사람의 레파지토리를 가져오고 복제한 후 PR날리는 법

다른 사람의 레파지토리에서 fork -> 내 레파지토리에서 포크된 레파지토리 주소를 복사 -> vscode 터미널실행 -> git clone 주소
-> git branch -v 브랜치 확인 -> 내 브렌치 만들기 git branch seongjune09 
-> seongjune09 브렌치로 이동 git checkout seongjune09 -> README.md 파일에서 글 수정 -> 저장 -> git add . 또는 git add README.md -> git commit "제목" -> git push origin seongjune09 