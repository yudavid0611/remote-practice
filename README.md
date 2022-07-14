# Remote Repository 연결하기

## Remote Repo 생성하기

### Github

1. 기본 브런치를 master로 변경하기
2. new Repo 생성하기
   1. 이름 설정
   2. 만들기

### Local

1. 새로운 디렉토리 생성
   1. mkdir remote-practice
   2. cd remote-practice
   3. git init
   4. git remote add orgin {url}
   5. git remote -> 연결 상태 확인
   6. touch README.md
2. 버전 남기기(push 전에 commit이 되어야 함)
   1. git add README.md
      - git add . -> wd의 모든 작업 add
   2. git commit -m '{message}'
3. git push orgin master
   - git push -u origin master -> 이후부터는 아래처럼 쓸 수 있음
     - git push