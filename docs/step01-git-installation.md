# STEP 01: Git 설치 안내

## 🎯 이 단계에서 배우는 것
Git이 무엇인지 알아보고, 우리 컴퓨터에 설치하는 과정입니다.

## 📚 Git이 뭔가요?
Git은 우리가 만드는 파일들의 변화를 기록해주는 도구입니다. 
마치 게임을 할 때 세이브 포인트를 여러 개 만들어두는 것처럼, Git은 우리의 파일 변화를 계속 기록해줍니다.

> Git = 파일의 변화를 자동으로 기록해주는 일기장 📝

## 💾 Git 설치하기

### 1단계: Git 다운로드 페이지 열기

1. 인터넷 브라우저(Chrome, Microsoft Edge 등)를 열어서 이 주소로 이동하세요:
   ```
   https://git-scm.com/install/windows
   ```

2. 화면에서 두 가지 버튼이 보일 거예요:
   - `Git for Windows/x64 Setup` (대부분의 경우)
   - `Git for Windows/ARM64 Setup` (최신 노트북이나 특별한 경우)

    > 🥕 대부분의 경우 `Git for Windows/x64 Setup`을 클릭해서 다운로드받으면 됩니다!

    ![Git 다운로드 페이지](/images/step01/1-installl-page.png)

### 2단계: 설치 프로그램 실행하기

1. 다운로드가 완료되면, 다운로드 폴더에서 **Git 설치 파일**을 찾으세요.
   - 파일 이름은 `Git-x.x.x-64-bit.exe` 같은 형태입니다.

2. 그 파일을 **더블클릭**해서 실행하세요.
    ![Windows 다운로드 폴더에서 Git 설치 파일 찾기](/images/step01/2-download-folder.png)

### 3단계: 설치 마법사 따라가기

설치 프로그램을 열면, 아래 사진처럼 설치 마법사 창이 나타납니다.
![Git 설치 마법사 첫 화면](/images/step01/3-git-installer.png)

1. 계속 "Next" 버튼을 클릭하세요.
2. 초록색 바가 끝까지 차면 설치가 완료되며 다음과 같은 화면이 나타납니다. 이때, "View Release Notes"를 클릭한 후 "Finish" 버튼을 클릭하세요.
    ![Git 설치 완료 화면](/images/step01/4-git-install-finish.png)

### 4단계: 설치 확인하기

설치가 잘 되었는지 확인해봅시다:

1. **윈도우 시작 메뉴**를 클릭하세요.
    ![Windows 시작 메뉴에서 명령 프롬프트 찾기](/images/step01/5-start-menu.png)
2. 왼쪽 아래 "프로그램 및 파일 검색" 부분을 클릭한 후, "cmd" 또는 "명령 프롬프트"를 검색하세요.
3. **cmd.exe**를 클릭해서 열으세요.
    ![명령 프롬프트 실행 첫 화면](/images/step01/6-open-cmd.png)


4. 검은 창이 열리면, 이 명령어를 입력하고 **Enter 키**를 누르세요:
   ```
   git --version
   ```

5. 화면에 다음과 같이 나타나면 **설치 성공**입니다! 🎉
   ```
   git version 2.x.x.windows.x
   ```
    ![Git 버전 확인 성공 화면](/images/step01/7-git-version.png)

## ✅ 완료!
Git이 성공적으로 설치되었습니다!

---

👉 다음: [STEP 02: GitHub 가입](./step02-github-signup.md)
