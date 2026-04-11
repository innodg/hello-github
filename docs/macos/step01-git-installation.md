# STEP 01: 깃 설치 안내 (macOS)

## 🎯 이 단계에서 배우는 것
깃(Git)이 무엇인지 알아보고, 우리 컴퓨터에 설치하는 과정입니다.

## 📚 깃(Git)이 뭔가요?
깃(Git)은 우리가 만드는 파일들의 변화를 기록해주는 도구입니다. 
마치 게임을 할 때 세이브 포인트를 여러 개 만들어두는 것처럼, 깃(Git)은 우리의 파일 변화를 계속 기록해줍니다.

> [!TIP]
> 깃(Git) = 파일의 변화를 자동으로 기록해주는 일기장 📝

## 💾 깃 설치하기

### 1단계: Homebrew(홈브류) 설치 여부 확인

macOS에서 깃을 설치하는 가장 쉬운 방법은 **홈브류**라는 패키지 관리 도구를 사용하는 것입니다.

> [!TIP]
> Homebrew(홈브류) = 프로그램을 쉽게 설치할 수 있게 도와주는 도구

`command + 스페이스 바`를 눌러 검색창을 열고, `terminal` 또는 `터미널`을 입력한 후, Enter 키를 눌러 터미널(terminal)을 실행합니다.

![터미널 검색](/docs/images/macos/step-01-image-01.png)

터미널(아래와 같은 창)에 `brew --version`을 입력하고 **Enter 키**를 누릅니다.

![Homebrew 버전 확인](/docs/images/macos/step-01-image-02.png)

**결과 확인**:

> [!NOTE]
> 결과에 따라 아래 두 가지 경우 중 하나를 따라 링크를 클릭해 이동합니다.

1. 아래 사진과 같이 홈브류를 이미 설치한 경우라면 `Homebrew x.x.x` 같은 메시지가 나타납니다 → [**2단계로 이동(클릭하기)**](#2단계-깃-설치하기)

  ![Homebrew 설치 여부 확인 결과 - 설치 된 경우](/docs/images/macos/step-01-image-03.png)

2. `Command 'brew' not found`와 같은 메시지가 나타나면 → [**1-1단계 진행(클릭하기)**](#1-1단계-홈브류-설치하기-설치하지-않은-경우)

  ![Homebrew 설치 여부 확인 결과 - 설치 안 된 경우](/docs/images/macos/step-01-image-04.png)

#### 1-1단계: 홈브류 설치하기 (설치하지 않은 경우)

터미널에 아래 텍스트를 **복사해서 붙여넣고** Enter 키를 누릅니다 :
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

![Homebrew 설치 명령어 입력](/docs/images/macos/step-01-image-05.png)

비밀번호를 입력하라는 메시지가 나타나면, **컴퓨터(노트북) 로그인 비밀번호**를 입력합니다. 이후, 마지막 줄에 `Press RETURN/ENTER to continue or any other key to abort:`와 같은 메시지가 나온 채로 정지해있다면 엔터 키를 누릅니다.

> [!TIP]
> 비밀번호를 입력할 때 화면에 아무것도 나오지 않지만 정상적인 상황이므로 신경쓰지 않아도 됩니다.

![Homebrew 설치 - 비밀번호 입력](/docs/images/macos/step-01-image-06.png)

설치가 끝날 때까지 기다립니다 (몇 분 정도 걸릴 수 있습니다).

> [!TIP]
> 아래 사진과 같이 텍스트를 입력할 수 있는 상태로 돌아오면 설치를 완료한 것입니다.

> [!CAUTION]
> 만약 `Next Steps`와 같은 추가 안내 문구가 나타난다면, 안내에 따라 추가로 텍스트를 입력해야합니다. 당황하지 말고 안내에 따라 텍스트를 복사해 붙여넣은 후, Enter 키를 누릅니다.
> 
> 아래와 같은 텍스트를 복사해 붙여넣으라고 안내하는 경우가 많습니다(그러나 추가 안내 내용이 다를 수 있으니, 안내 내용을 잘 읽어야합니다).
> ```bash
> echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> /Users/사용자이름/.zprofile
> ```

![Homebrew 설치 완료](/docs/images/macos/step-01-image-07.png)

### 2단계: 깃 설치하기

터미널에 `brew install git`를 입력한 후, Enter 키를 누릅니다.

![깃 설치 명령어 입력](/docs/images/macos/step-01-image-08.png)

설치를 완료할 때까지 기다립니다 (몇 분 정도 걸릴 수 있습니다).

> [!TIP]
> 아래 사진과 같이 글자를 입력할 수 있는 상태로 돌아오면 설치를 완료한 것입니다.

![깃 설치 완료](/docs/images/macos/step-01-image-09.png)

### 3단계: 설치 확인하기

설치를 잘 했는지 확인해보겠습니다.

터미널에 `git --version`을 입력하고 Enter 키를 누릅니다.

![깃 버전 확인 명령어 입력](/docs/images/macos/step-01-image-10.png)

화면에 `git version x.x.x` 글자가 보이면 **설치 성공**입니다! 🎉

![깃 버전 확인 성공](/docs/images/macos/step-01-image-11.png)

## ✅ 완료!
깃을 성공적으로 설치했습니다!

---

👉 다음: [STEP 02: 깃허브 가입](/docs/step02-github-signup.md)
