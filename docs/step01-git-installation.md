# STEP 01: Git 설치 안내

## 🎯 이 단계에서 배우는 것
Git이 무엇인지 알아보고, 우리 컴퓨터에 설치하는 과정입니다.

## 📚 Git이 뭔가요?
Git은 우리가 만드는 파일들의 변화를 기록해주는 도구입니다. 
마치 게임을 할 때 세이브 포인트를 여러 개 만들어두는 것처럼, Git은 우리의 파일 변화를 계속 기록해줍니다.

> [!TIP]
> Git = 파일의 변화를 자동으로 기록해주는 일기장 📝

> [!IMPORTANT]
> 🍎 **macOS 사용자**(맥북, 아이맥 등)는 [macOS용 STEP 01 문서](./macos/step01-git-installation.md)로 이동해주세요.

## 💾 Git 설치하기

### 1단계: Git 다운로드 페이지 열기

1. 인터넷 브라우저(Microsoft Edge, Chrome 등)를 열어서 주소창에 `https://git-scm.com/install/windows`를 입력하세요.
   
   ![url 입력](/docs/images/step-01-image-01.png)

2. 화면에서 두 가지 버튼이 보일 거예요:
   - `Git for Windows/x64 Setup` (대부분의 경우)
   - `Git for Windows/ARM64 Setup` (최신 노트북이나 특별한 경우)

    > [!TIP]
    > 대부분의 경우 `Git for Windows/x64 Setup`을 클릭해서 다운로드받으면 됩니다!

    ![Git 다운로드 페이지](/docs/images/step-01-image-02.png)

### 2단계: 설치 프로그램 실행하기

1. 다운로드가 완료되면, 다운로드 폴더에서 **Git 설치 파일**을 찾으세요.
   > [!TIP]
   > 파일 이름은 `Git-x.x.x-64-bit` 같은 형태입니다.

2. 그 파일을 **더블클릭**해서 실행하세요.

    ![Windows 다운로드 폴더에서 Git 설치 파일 찾기](/docs/images/step-01-image-03.png)

### 3단계: 설치 마법사 따라가기

1. `이 앱이 디바이스를 변경할 수 있도록 허용하시겠어요?`와 같은 메시지가 나오면, `예` 버튼을 클릭하세요. 그럼 아래 사진처럼 설치 마법사 창이 나타납니다.

    > [!TIP]
    > 아무 설정도 건드리지 않고 계속 `Next` 버튼만 클릭하면 됩니다!

    ![Git 설치 마법사 첫 화면](/docs/images/step-01-image-04.png)
2. 초록색 바가 끝까지 차면 설치가 완료되며 다음과 같은 화면이 나타납니다. 이때, `View Release Notes`를 클릭한 후 `Finish` 버튼을 클릭하세요.

    ![Git 설치 완료 화면](/docs/images/step-01-image-05.png)

### 4단계: 설치 확인하기

설치가 잘 되었는지 확인해봅시다.

1. **윈도우 시작 메뉴**를 클릭하세요.

    ![Windows 시작 메뉴에서 명령 프롬프트 찾기](/docs/images/step-01-image-06.png)
2. 이후 아래 사진처럼 검색창에 `cmd` 또는 `명령 프롬프트`를 검색하세요.

    ![명령 프롬프트 검색 화면](/docs/images/step-01-image-07.png)

3. 검색한 내용들 중 `명령 프롬프트` 또는 `cmd`를 더블 클릭하면, 아래 사진처럼 검은 창이 나타납니다.

    ![명령 프롬프트 실행 첫 화면](/docs/images/step-01-image-08.png)


4. 검은 창이 열리면, `git --version`을 입력하고 Enter 키를 누르세요.

    ![git --version 입력 화면](/docs/images/step-01-image-09.png)

5. 화면에 `git version 2.x.x.windows.x`와 같은 메시지가 나타나면 **설치 성공**입니다! 🎉

    ![Git 버전 확인 성공 화면](/docs/images/step-01-image-10.png)

## ✅ 완료!
Git이 성공적으로 설치되었습니다!

---

👉 다음: [STEP 02: GitHub 가입](./step02-github-signup.md)
