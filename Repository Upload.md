# Git-Tutorial

## Repository Upload 하는 법

### GitBash 환경설정
1. Name 설정
- git config --global user.name "your_name"
2. Email 설정
- git config --global user.email "your_email"
3. 세팅 정보 확인 (user.name, user.email 확인)
- git config --list

### Project Upload
1. init
- git init
2. 업로드 파일 설정하기
- git add 파일명
3. 파일 정보 확인
- git status
4. 히스토리 설정
- git commit -m "first commit"
5. Repository 경로 연결
- git remote add origin git@github.com:SeoSuHong/Git-Tutorial.git
6. 연결 설정 확인
- git remote -v
7. 프로젝트 보내기
- git push origin master

### Project Update
1. 업데이트 파일 설정하기
- git add 파일명
2. 파일 정보 확인
- git status
3. 히스토리 설정
- git commit -m "second commit"
4. 프로젝트 보내기
- git push origin master
