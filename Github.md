# Github 이용방법

1. cmd에서 cd 로컬repo로 시작<br>

2. 파일 받기
git pull

3. 파일 수정
git add DBupdater.py나 git add *<br>
git commit -m "2021-07-04 07:20 Lutris98"<br>
git push<br>

+ 파일별 원격repo 관리<br>
git remote add origin https://github.com/Lutris98/21_3Q.git<br>
만약 다른 파일로 전환한 거면 전에 git remove origin 부터<br>
(git remote -v로 확인 가능)<br>
(git status로 파일 업로드 상태 확인가능)<br>

+main과 origin/main이 자동 diverged<br>
git commit -am "Dongjun"<br>
git push origin<br>