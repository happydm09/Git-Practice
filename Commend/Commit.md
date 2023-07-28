# 커밋

1. git add [파일 이름]
> 커밋할 파일을 고르기

       git add .
- 모든 파일: '.' (마침표 하나) <br>
- 두 개 이상: 띄어쓰기로 구분  예) git add main.py test.py <br>
- 디렉토리(폴더): <폴더명>     예) git add Test

<br>

2. git commit -m "메시지"
> 파일을 커밋

       git commit -m "commit"
- 예) git commit -m "test commit"

<br>

## 깃허브에 올리기

3. git branch -M [가지 이름]
> 가지(branch)를 설정

       git branch -M main
- 예) git branch -M main

<br>

4. git remote add origin [깃허브 저장소 URL].git
> 리모트(저장소) 추가

       git remote add origin https://github//.git
- 예) git remote add origin https://github/happydm09/Git-Pracitce.git

<br>

5. git push -u origin [가지 이름]
> push(깃허브에 아까 지정해 놓은 저장소, 가지에 저장)

       git push -u origin main
- 예) git push -u origin main