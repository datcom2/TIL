# 2일차 정리
- 오늘 배운 내용을 정리해보는 시간을 가져봅시다.
- vscode상에서 git add -> commit -> push 하는 과정까지 완료해 봅시다.

## github 특강
### Github
- git init
- git remote add [이름] [깃허브주소] : 원격저장소 등록
- git remote rm [이름] : 원격 저장소 연결 삭제
- git remote -v : 원격 저장소 조회

- git add [파일명]
- git commit -m "[메세지]"
- git status
- git log, git log --oneline

- git push [저장소명] [브랜치명] : 로컬 -> 원격 업로드
---
### .gitignore
- 특정 파일, 폴더를 Git이 버전 관리를 하지 못하도록 지정하는 것
- .은 숨김파일이라는 뜻
- git add 전에 먼저 .gitignore를 작성
- https://www.toptal.com/developers/gitignore - ignore 사용자 환경에 맞게 쉽게 작성해주는 사이트

### clone, pull
- git clone
    - 원격저장소의 커밋내역을 모두 가져와서, 로컬 저장소를 생성하는 명령어
    - git clone [원격 저장소 주소]

- git pull
    - 원격 저장소의 변경 사항을 가져와서, 로컬 저장소를 업데이트하는 명령어
    - git pull [저장소명] [브랜치명]