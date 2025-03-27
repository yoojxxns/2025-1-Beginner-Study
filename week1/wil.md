이번 시간에는 개발 입문 스터디 1주차로 git의 이용방법등을 배우고 실습을 해보았다.
깃의 존재 이유는 크게 개발자들이 프로젝트를 같이 진행할때 최대한 편하게 하기 위함이라고 할 수 있다.
각종 코드의 수정을 관리하고 파일들도 정리 및 관리하고 버전 관리도 해야하는 것이다.

파일의 생명주기에는 Untracked, Unmodified, Modified, Staged 이렇게 4단계가 있다.
git의 흐름에는 Working Directory, Staging Area, Local Repository, Remote Repository 4단계가 있다
Working Directory에서 Staging Area 로 파일을 넘길 때에는 git add 명령어를 사용하고
Staging Area 에서 Local Repo로 넘어갈 때는 git commit 명령어를 사용,
Local Repo 에서 Remote Repo로 넘길때는 git push 명령어를 사용한다.

또한 Commit message 라는 것이 있는데
본인이 수정한 것들을 다른 사람들에게 알려주기 위해 사용한다.

