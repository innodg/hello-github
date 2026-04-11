# STEP 04: 깃허브 저장소 생성 (macOS)

## 🎯 이 단계에서...
깃허브 데스크탑(GitHub Desktop)을 사용하여 내 맥(맥북, 아이맥 등)에서 저장소(Repository)를 만들고, 이를 깃허브(GitHub)에 업로드합니다.

## 📚 저장소(Repository)가 뭔가요?
저장소(Repository)는 마치 폴더처럼 우리의 파일들을 모아두는 공간입니다.
다만 일반 폴더와 다르게, **우리가 파일을 어떻게 수정했는지 기록**할 수 있습니다.

> [!TIP]
> 저장소(Repository) = 우리 파일들을 저장하는 폴더 + 내용 변화 기록 📁

## 🔨 내 맥에서 저장소 만들고 깃허브에 업로드하기

### 1단계: 깃허브 데스크탑 실행

만약 깃허브 데스크탑을 실행하고 있지 않다면, `command + Space`를 눌러 검색창에서 `GitHub Desktop`을 검색해 실행합니다.

실행하면 아래 사진과 같은 화면이 보입니다.

![깃허브 데스크탑 실행 화면](/docs/images/macos/step-03-image-15.png)

### 2단계: 새 저장소 만들기

맥 화면 **맨 위 메뉴 막대**에서 `File` 메뉴를 클릭합니다.

> [!TIP]
> 윈도우와 달리, 맥에서는 메뉴가 깃허브 창 안이 아니라 **화면 맨 위**에 나타납니다.

![File 메뉴 클릭](/docs/images/macos/step-04-image-01.png)

`New Repository...`를 선택합니다.

![File 메뉴에서 New Repository 선택](/docs/images/macos/step-04-image-02.png)

### 3단계: 저장소 정보 입력하기

새 저장소 생성 창이 열립니다. 여기서 우리의 저장소 정보를 입력합니다.

![새 저장소 생성 창](/docs/images/macos/step-04-image-03.png)

#### Name(저장소 이름)

"Name" 칸에 `my-first-project`를 입력합니다.

> [!NOTE]
> 다른 저장소 이름을 사용해도 상관없지만, 이번 시간에는 `my-first-project`로 저장소 이름을 설정합니다.

![저장소 이름 입력](/docs/images/macos/step-04-image-04.png)

#### Description(설명)

"Description" 칸은 선택사항입니다. 우리 저장소가 어떤 목적의 저장소인지 간단히 설명하는 입력 칸입니다.

> [!TIP]
> **예시**
> - 깃허브를 배우는 첫 번째 프로젝트입니다.
> - 나의 코딩 연습용 저장소입니다.

![저장소 설명 입력 예시](/docs/images/macos/step-04-image-05.png)

#### Local Path(로컬 경로)

"Local Path"에서 `Choose...` 버튼을 클릭하여 저장소를 만들 위치를 선택합니다.

![로컬 경로 선택 버튼](/docs/images/macos/step-04-image-06.png)

> [!NOTE]
> 아래 사진처럼 "Desktop" 폴더를 선택한 후, `열기` 버튼을 클릭합니다(다른 폴더를 선택해도 되지만, 이번 시간에는 "Desktop" 폴더에 저장소를 만들도록 하겠습니다).
>
> ![로컬 경로 선택 예시](/docs/images/macos/step-04-image-07.png)

#### 리드미 초기화

"Initialize this repository with a README" 박스를 클릭합니다.

![README 초기화 체크박스](/docs/images/macos/step-04-image-08.png)

> [!TIP]
> **리드미란?**
> 리드미는 우리 저장소에 대해 설명하는 파일입니다. 마치 책의 앞표지처럼, 다른 사람들이 우리 저장소를 이해할 수 있도록 도와줍니다(물론 우리가 리드미에 내용을 작성해야 합니다).

### 4단계: 저장소 만들기

모든 정보를 입력했으면, **"Create Repository"** 버튼을 클릭합니다.

![Create Repository 버튼](/docs/images/macos/step-04-image-09.png)

그럼 이제 화면이 바뀌며 우리가 만든 `my-first-project` 저장소가 보입니다.

![새로 만든 저장소 화면](/docs/images/macos/step-04-image-10.png)

### 5단계: 깃허브에 저장소 업로드하기

이제 우리 맥에 만든 저장소를 깃허브에 업로드해봅시다!

깃허브 데스크탑 오른쪽 위에 있는 `Publish repository` 버튼을 클릭합니다.

![Publish repository 버튼](/docs/images/macos/step-04-image-11.png)

새 창이 열리면, "Keep this code private" 박스를 클릭해 체크를 해제함으로써 다른 사람들이 우리 저장소를 볼 수 있도록 설정합니다. 그리고 `Publish repository` 버튼을 클릭합니다.

![Publish repository 설정 창](/docs/images/macos/step-04-image-12.png)

> [!TIP]
> 깃허브에 저장소를 업로드할 때, 잠시 기다려야 합니다.

### 6단계: 깃허브에서 확인하기

화면 맨 위 메뉴 막대에서 `Repository`를 클릭합니다.

![Repository 메뉴 클릭](/docs/images/macos/step-04-image-13.png)

`View on GitHub`를 클릭합니다.

![Repository 메뉴에서 View on GitHub 선택](/docs/images/macos/step-04-image-14.png)

웹 브라우저(Microsoft Edge, Chrome 등)가 열리면서 깃허브에 업로드된 저장소를 확인할 수 있습니다!

![깃허브에 업로드된 저장소 확인](/docs/images/macos/step-04-image-15.png)

## ✅ 완료!
축하합니다! 🎉 깃허브 데스크탑으로 내 맥에 저장소를 만들고 깃허브에 업로드했습니다!

### 마지막 단계: 만들었던 폴더 제거하기

다음 단계에서 깃허브에 업로드한 저장소를 내 맥으로 복제해오는 연습을 하기 위해, 방금 만든 폴더를 제거해봅시다.

화면 맨 위 메뉴 막대에서 `Repository`를 클릭합니다.

![Repository 메뉴 클릭](/docs/images/macos/step-04-image-13.png)

`Remove...`를 클릭합니다.

![Repository 메뉴에서 Remove 선택](/docs/images/macos/step-04-image-16.png)

아래 사진처럼 **"Also move this repository to Trash"**(휴지통으로 이동) 박스를 클릭해 체크함으로써 내 맥에서 저장소를 완전히 삭제하도록 설정합니다. 그리고 `Remove` 버튼을 클릭합니다.

![Remove 확인 창](/docs/images/macos/step-04-image-17.png)

> [!NOTE]
> **왜 삭제하나요?**
> 방금 우리는 저장소를 깃허브에 업로드했으니 걱정하지 않아도 됩니다. 다음 단계에서 우리는 깃허브에 있는 저장소를 내 컴퓨터로 복제해오는 연습을 할 예정입니다.

이제 우리는 **깃허브 데스크탑**을 설치하고, **깃허브 계정**을 만들고, **저장소**도 만들어서 **깃허브에 업로드**했습니다!

---

👈 이전: [STEP 03: 깃허브 데스크탑 설치 안내](/docs/macos/step03-github-desktop-installation.md)

👉 다음: [STEP 05: 깃허브 데스크탑으로 저장소 클론](/docs/macos/step05-clone-repository.md)