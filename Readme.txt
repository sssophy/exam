## 처음으로 깃/깃허브 설정하기
## 이름 설정
git config --global user.name "sssophy"
## 이메일 설정
git config --global user.email "sssophy2941@gmail.com"

## Local Repository 생성
mkdir ~/MyProject
## Local Repository 초기화
#cd ~/MyProject
git init
# 파일 생성
touch Readme.txt
# git 상태확인
git status
# git 에 파일 추가
git add Readme.txt
# git 에 커밋
git commit -m "Add Readme.txt"
# git remote 설정 (online repository 연결)
git remote add origin https://github.com/sssophy/exam.git
# git remote setting
git remote -v
# git push
git push origin master


