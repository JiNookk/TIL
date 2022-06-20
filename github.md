

commit


push

fetch
  - 브랜치 생성전 필요한 내용을 원격저장소로부터 받아 .git파일에 집어넣는 명령어

branch
  개발하다보면 하나의 코드를 여러 개로 복사해야 하는 일이 생긴다.
  기존의 코드와 독립적으로 개발을 진행할 수 있는데, 이렇게 독립적으로 개발하는게 브랜치다.
  
  - 브랜치 생성방법
    git checkout -b yj_develop(그냥 로컬브랜치 만들기)
    git switch -c main origin/main(원격저장소의 내용을 받아와서 로컬 main 브랜치 생성 -> fetch 선행해야 가능.)

Fork
  다른 사람의 github repo에서 내가 어떤 부분을 수정하거나 추가 기능을 넣고 싶을 때 해당 repo를 내 repo로 가져오는 기능이다.
  흔히 포크를 뜬다고 표현한다.

Pull request
  내가 수정한 코드가 있으니 내 branch를 가져가 검토 후 병합해주세요!라는 일련의 과정
  코드 충돌을 최소화할 수 있고 push 권한이 없는 오픈 소스 프로젝트에 기여할 때 많이 사용한다.
  
  순서
    - Fork
      -> fork가 완료되면 url이 내 깃헙에 맞추어 변경됨!
    - clone, remote 설정
      -> 내 로컬저장소에 fork한 repo를 clone한다.
    - branch 설정
      -> 
    - 수정 작업 후 add, commit, push
    - Pull request 생성
    - Merge Pull Request
    - Merge 이후 동기화 및 branch 삭제
    





