# STEP 01: Git 설치 안내 (macOS)

## 🎯 이 단계에서 배우는 것
Git이 무엇인지 알아보고, 우리 컴퓨터에 설치하는 과정입니다.

## 📚 Git이 뭔가요?
Git은 우리가 만드는 파일들의 변화를 기록해주는 도구입니다. 
마치 게임을 할 때 세이브 포인트를 여러 개 만들어두는 것처럼, Git은 우리의 파일 변화를 계속 기록해줍니다.

> [!TIP]
> Git = 파일의 변화를 자동으로 기록해주는 일기장 📝

## 💾 Git 설치하기

### 1단계: Homebrew 설치 여부 확인

macOS에서 Git을 설치하는 가장 쉬운 방법은 **Homebrew**라는 패키지 관리 도구를 사용하는 것입니다.

> [!TIP]
> Homebrew = 프로그램을 쉽게 설치할 수 있게 도와주는 도구

1. `cmd + space` 키를 눌러 **검색**창을 열고, `terminal` 또는 `터미널`을 입력한 후, 엔터 키를 누릅니다.

   ![터미널 검색](/docs/images/macos/step-01-image-01.png)

2. 터미널(아래와 같은 창)에 `brew --version`을 입력하고 **Enter 키**를 누르세요.

   ![Homebrew 버전 확인](/docs/images/macos/step-01-image-02.png)
   
3. **결과 확인**:

   > [!NOTE]
   > 결과에 따라 아래 두 가지 경우 중 하나를 따라가주시면 됩니다.

   - 아래 사진과 같이 Homebrew가 설치되어 있으면 `Homebrew x.x.x` 같은 메시지가 나타납니다 → [**2단계로 이동(클릭하기)**](#2단계-git-설치하기)
      ![Homebrew 설치 여부 확인 결과 - 설치 된 경우](/docs/images/macos/step-01-image-03.png)

   - `Command 'brew' not found`와 같은 메시지가 나타나면 → [**1-1단계 진행(클릭하기)**](#1-1단계-homebrew-설치하기-설치되어-있지-않은-경우)
      ![Homebrew 설치 여부 확인 결과 - 설치 안 된 경우](/docs/images/macos/step-01-image-04.png)

#### 1-1단계: Homebrew 설치하기 (설치되어 있지 않은 경우)

1. 터미널에 다음 명령어를 **복사해서 붙여넣고** Enter 키를 누르세요:
   ```
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
   ```

   ![Homebrew 설치 명령어 입력](/docs/images/macos/step-01-image-05.png)

2. 비밀번호를 입력하라는 메시지가 나타나면, **컴퓨터(노트북) 로그인 비밀번호**를 입력하세요. 이후, 마지막 줄에 `Press RETURN/ENTER to continue or any other key to abort:`와 같은 메시지가 나온 채로 정지해있다면 엔터 키를 눌러주세요.

   > [!TIP]
   > 비밀번호를 입력할 때 화면에 아무것도 표시되지 않지만, 정상적으로 입력되고 있습니다.

   ![Homebrew 설치 - 비밀번호 입력](/docs/images/macos/step-01-image-06.png)

3. 설치가 완료될 때까지 기다리세요. (몇 분 정도 걸릴 수 있습니다)

   > [!TIP]
   > 아래 사진과 같이 텍스트를 입력할 수 있는 상태로 돌아오면 설치가 완료된 것입니다.

   > [!CAUTION]
   > 만약 `Next Steps`와 같은 추가 안내 문구가 나타난다면, 안내에 따라 추가로 텍스트를 입력해야합니다. 당황하지 말고 안내에 따라 텍스트를 복사해 붙여넣은 후, Enter 키를 눌러주세요.
   > 
   > 아래와 같은 텍스트를 복사해 붙여넣으라고 안내하는 경우가 많습니다(그러나 추가 안내 내용이 다를 수 있으니, 안내를 잘 읽어주세요).
   > ```bash
   > echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> /Users/사용자이름/.zprofile
   > ```

   ![Homebrew 설치 완료](/docs/images/macos/step-01-image-07.png)

### 2단계: Git 설치하기

1. 터미널에 `brew install git`를 입력한 후, Enter 키를 누르세요.

   ![Git 설치 명령어 입력](/docs/images/macos/step-01-image-08.png)

2. 설치가 완료될 때까지 기다리세요. (몇 분 정도 걸릴 수 있습니다)

   > [!TIP]
   > 아래 사진과 같이 글자를 입력할 수 있는 상태로 돌아오면 설치가 완료된 것입니다.

   ![Git 설치 완료](/docs/images/macos/step-01-image-09.png)

### 3단계: 설치 확인하기

설치가 잘 되었는지 확인해보겠습니다.

1. 터미널에 `git --version`을 입력하고 Enter 키를 누르세요.

   ![Git 버전 확인 명령어 입력](/docs/images/macos/step-01-image-10.png)

2. 화면에 `git version x.x.x` 글자가 보이면 **설치 성공**입니다! 🎉

   ![Git 버전 확인 성공](/docs/images/macos/step-01-image-11.png)

## ✅ 완료!
Git이 성공적으로 설치되었습니다!

---

👉 다음: [STEP 02: GitHub 가입](/docs/step02-github-signup.md)
