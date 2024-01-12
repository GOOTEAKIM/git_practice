# 깃 연습중

# GIT

- 깃 시작하기 `git init`
- 현재 로컬 저장소의 파일 상태 보기 `git status`
- 깃 추가하기 `git add 폴더나 파일명`
- 깃 커밋하기 `git commit -m "제목" `
- 파일 만들기 `touch 파일명`
- 시작하기 `start 폴더명`
- 더하기 `git add 폴더`
- `cd 폴더명` 작업하려는 폴더로 이동
  > 사용자 이름이랑 메일을 입력하라고 함
  - 메일 입력 `git config --global user.email "gootae0220@naver.com" `
  - 이름 입력 `git config --global user.name "김구태" `
- 작성한 사용자 정보 확인 `git config --global --list`
- 커밋 만들기 `git commit -m "커밋 이름`
- 커밋 history 확인 `git log`
- commit 목록 한 줄로 보기 `git log --oneline`
- 깃 커밋 수정하기 `git commit --amend`
- 리모트 연결 `git remote add origin 주소`
- 리모트 되어 있는거 확힌 `git remote -v`
- `git push 푸쉬할 것 이름 master`
- `git push origin master`
- 붙여넣기 `shift + insert 아니면 우클릭`
- 내려받기 `git pull 파일이름 master`
  
- 깃과 깃랩은 다르다.
- 깃허브는 조금 더 오픈되어 있는 느낌이다.

- 집에 가서 아카데미의 폴더를 최초로 열 때  `git clone 깃랩의 주소`
- 그 이후부터는? ``

  # GITHUB

  - branch? 작업 공간
  - `repository name` 아무거나 해도 됨
  - `Add a README file` 빈 폴더를 하나 만든다고 생각하면됨. 원격 저장소 만들 때에는 체크하지 않는다.
  - `gitignore`
  - CLI(명령어) 로 업로드 한다.

# 와서 해야할 루틴
1. 강의장에서 (academy 폴더에서) 새 파일 생성
2. add commit push (gitlab으로 푸시)
3. 집 (home 폴더에서) git pull
4. 집에서 새 파일 생성
5. add commit push (gitlab으로 푸시)
6. 강의장에서 git pull gitlab master
