Github 으로 과제 제출하기 🥲
=

<br />

1️⃣ AND-SOPT-WEB Organization 접속
-
<img width="1264" alt="image" src="https://github.com/user-attachments/assets/abf3e375-17fa-4320-9ea1-934a04e1c037">

[AND-SOPT-WEB 바로가기
](https://github.com/AND-SOPT-WEB)

_AND-SOPT-WEB 팔로우도 한번 누르기_ 😁

<br />

2️⃣ 본인 Repository 찾기
-
<img width="1358" alt="image" src="https://github.com/user-attachments/assets/2d9801ca-40e5-43a7-9e89-7ffaa38a2374">

내 이름으로 만들어진 repository를 찾습니다.

<br />

3️⃣ Repository URL 복사
-
<img width="1892" alt="image" src="https://github.com/user-attachments/assets/dd88cfe0-c56b-491a-b7b1-687ceac3d1bc">

내 Repository의 URL을 복사해줍니다.

<br />

4️⃣ Repository 클론하기
-
![image](https://github.com/user-attachments/assets/750c7bc8-cdda-4c49-8068-b120be7217ed)

터미널을 열고, Repository를 클론 받을 폴더로 이동합니다.

```shell
git clone https://github.com/AND-SOPT-WEB/레포지토리명.git
```
폴더로 이동했다면, 클론 명령어를 입력합니다.

ls 명령어를 통해, 클론이 정상적으로 되어서 레포지토리 폴더가 생긴 것을 확인할 수 있습니다. (그저 확인용 명령어, 안해도 상관없음)

_터미널은 Mac 이라면(터미널, iTerm) Window라면(PowerShell, Git Bash)를 추천합니다.
윈도우의 명령프롬프트(cmd)도 가능하지만 명령어가 다릅니다._

<br />

5️⃣ 클론 받은 Repository를 VSCode를 통해 열기
-

![image](https://github.com/user-attachments/assets/d369bfb9-8258-4efe-96b2-712987648258)

```shell
cd [폴더명] // clone 받은 폴더로 이동
code . // 해당 폴더를 vscode에서 열어줌
```

<br />

6️⃣ 브랜치 생성하기
-

브랜치는 작업환경을 분리해주는 친구입니다.
우리는 매주(혹은 각) 과제마다 브랜치를 생성할거에요.

1주차 과제를 진행한다고 가정하고 week1 이라는 브랜치를 만들어보겠습니다.

다음 명령어를 통해서 week1 브랜치를 생성할 수 있습니다.

```shell
git branch week1 // 브랜치 생성
git checkout week1 // 브랜치 이동

또는

git checkout -b week1 // 브랜치를 생성하고 이동
```

```shell
git branch
```
위 명령어를 통해, 현재 생성된 브랜치들과 내가 있는 브랜치를 확인할 수 있습니다!

7️⃣ 생성한 브랜치에서 작업하고 커밋하기
-

 브랜치에서 작업을 다했다면

```shell
git add .
git commit -m "커밋 메시지"
git push origin week1
```
명령어를 통해, 커밋을 남기고 Github 에 커밋을 Push합니다.

마지막으로, Gihub의 해당 브랜치로 가서 작업내용이 잘 올라갔는지 확인해줍니다!
