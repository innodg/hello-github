# STEP 01: 깃 설치 안내

## 🎯 이 단계에서 배우는 것
깃(Git)이 무엇인지 알아보고, 우리 컴퓨터에 설치하는 과정입니다.

## 📚 깃(Git)이 뭔가요?
깃(Git)은 우리가 만드는 파일들의 변화를 기록해주는 도구입니다. 
마치 게임을 할 때 세이브 포인트를 여러 개 만들어두는 것처럼, 깃(Git)은 우리의 파일 변화를 계속 기록해줍니다.

> [!TIP]
> 깃(Git) = 파일의 변화를 자동으로 기록해주는 일기장 📝

> [!IMPORTANT]
> 🍎 **macOS 사용자**(맥북, 아이맥 등)는 기본적으로 맥에 존재하는 깃(Git)을 사용할 예정입니다. 곧바로 [STEP02 : 깃허브(GitHub) 가입](/docs/step02-github-signup.md)으로 이동합니다.

## 💾 깃 설치하기

### 1단계: 깃 다운로드 페이지 열기

인터넷 브라우저(Microsoft Edge, Chrome 등)를 열어서 주소창에 `https://git-scm.com/install/windows`를 입력합니다.

![url 입력](/docs/images/step-01-image-01.png)

화면에서 두 가지 링크가 보입니다. 본인 컴퓨터에 알맞은 링크를 클릭해 다운로드하세요 :
- `Git for Windows/x64 Setup` (대부분의 경우)
- `Git for Windows/ARM64 Setup`

![깃 다운로드 페이지](/docs/images/step-01-image-02.png)

### 2단계: 설치 프로그램 실행하기

다운로드가 완료되면, 다운로드 폴더에서 **깃 설치 파일**을 찾습니다. 그리고 그 파일을 더블클릭해 실행합니다.
> [!TIP]
> 파일 이름은 `Git-x.x.x-64-bit` 같은 형태입니다.

![Windows 다운로드 폴더에서 깃 설치 파일 찾기](/docs/images/step-01-image-03.png)

### 3단계: 설치 마법사 따라가기

`이 앱이 디바이스를 변경할 수 있도록 허용하시겠어요?`와 같은 메시지가 나오면, `예` 버튼을 클릭합니다. 그럼 아래 사진처럼 설치 마법사 창이 나타납니다. 아무 설정도 건드리지 않고 계속 `Next` 버튼만 클릭합니다.

![깃 설치 마법사 첫 화면](/docs/images/step-01-image-04.png)

초록색 바가 끝까지 차면 설치를 완료한 것입니다. 그럼 다음과 같은 화면이 나타납니다. 이때, `View Release Notes`를 클릭해 체크 표시가 나오도록 한 후 `Finish` 버튼을 클릭하세요.

![깃 설치 완료 화면](/docs/images/step-01-image-05.png)

### 4단계: 설치 확인하기

설치를 잘 했는지 확인합니다.

**윈도우 시작 메뉴**를 클릭합니다.

![Windows 시작 메뉴에서 명령 프롬프트 찾기](/docs/images/step-01-image-06.png)

이후 아래 사진처럼 검색창에 "cmd" 또는 "명령 프롬프트"를 검색합니다.

![명령 프롬프트 검색 화면](/docs/images/step-01-image-07.png)

검색한 내용들 중 "명령 프롬프트" 또는 "cmd"를 클릭하면, 아래 사진처럼 검은 창이 나타납니다.

![명령 프롬프트 실행 첫 화면](/docs/images/step-01-image-08.png)


검은 창이 열리면, `git --version`을 입력하고 Enter 키를 누릅니다.

![git --version 입력 화면](/docs/images/step-01-image-09.png)

화면에 `git version 2.x.x.windows.x`와 같은 메시지가 나타나면 **설치 성공**입니다! 🎉

![깃 버전 확인 성공 화면](/docs/images/step-01-image-10.png)

## ✅ 완료!
깃을 성공적으로 설치했습니다!

---

👉 다음: [STEP 02: 깃허브 가입](/docs/step02-github-signup.md)
