# GIT TEST

### git 명령어


1. `git init` - git을 초기화한다. `'.git'` 폴더가 생긴다. 해당 폴더에서 git 명령어들을 사용할 수 있게 된다.

2. `git add` - git에 stage할 파일을 추가한다. `.`을 뒤에 붙여 모든 변동된 파일을 추가하거나 특정한 파일만 추가할 수  있다. stage된 파일들은 git에 추적된다.

3. `git commit` - stage된 파일들의 변동된 내역들을 로컬 스토리지에 저장한다. 자세한 메시지를 남길 수도 있고 `-m` 을 사용해 간단한 메시지를 남길 수도 있다. 

4. `git push` - 로컬 스토리지에 commit한 내역들을 remote, 즉 원격 스토리지인 github에 올려 동기화한다. push한 브랜치가 main브랜치가 아닐 경우 바로 동기화되지 않고 남아 pull request을 열 수 있으며 github에서 해당 기능을 통해 브랜치가 수정한 내역을 확인 및 수정하고 main브랜치에 merge하여 동기화한다.
