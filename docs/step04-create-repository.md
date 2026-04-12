# STEP 04: GitHub 저장소 생성

## 🎯 이 단계에서 배우는 것
깃허브 데스크탑(GitHub Desktop)을 사용하여 로컬에서 저장소(Repository)를 만들고, 이를 깃허브(GitHub)에 업로드합니다.

## 📚 저장소(Repository)가 뭔가요?
저장소(Repository)는 마치 폴더처럼 우리의 파일들을 모아두는 공간입니다. 다만 일반 폴더와 다르게, **우리가 파일을 어떻게 수정했는지 기록**할 수 있습니다.

> [!TIP]
> 저장소(Repository) = 우리 파일들을 저장하는 폴더 + 내용 변화 기록 📁

> [!IMPORTANT]
> 🍎 **macOS 사용자**(맥북, 아이맥 등)는 [macOS용 STEP 04 문서](/docs/macos/step04-create-repository.md)를 클릭해 이동합니다.

## 🔨 내 컴퓨터(노트북)에서 저장소 만들고 깃허브에 업로드하기

### 1단계: 깃허브 데스크탑 실행

만약 깃허브 데스크탑을 실행하고 있지 않다면, 깃허브 데스크탑을 실행합니다.

> [!TIP]
> 깃허브 데스크탑 실행을 위해 다음 단계를 수행합니다 :
> 1. **윈도우 시작 메뉴**를 클릭합니다.
> 2. 검색칸("프로그램 및 파일 검색" 부분)을 클릭한 후, "GitHub Desktop"을 검색합니다.
> 3. **GitHub Desktop**을 클릭해서 실행합니다.

![깃허브 데스크탑 실행 화면](/docs/images/step-04-image-01.png)

### 2단계: 새 저장소 만들기

왼쪽 상단의 `File` 메뉴를 클릭합니다.

![File 메뉴 클릭](/docs/images/step-04-image-02.png)

`New Repository...`를 선택합니다.

![File 메뉴에서 New Repository 선택](/docs/images/step-04-image-03.png)

### 3단계: 저장소 정보 입력하기

새 저장소 생성 창이 열립니다. 여기서 우리의 저장소 정보를 입력합니다.

![새 저장소 생성 창](/docs/images/step-04-image-04.png)

#### Name(저장소 이름)

"Name" 칸에 `my-first-project`를 입력합니다.

> [!NOTE]
> 다른 저장소 이름을 사용해도 괜찮지만, 이번 시간에는 `my-first-project`로 저장소 이름을 설정합니다.

![저장소 이름 입력](/docs/images/step-04-image-05.png)

#### Description(설명)

"Description" 칸은 선택사항이라 내용을 적지 않아도 괜찮습니다. Description 칸에는 우리 저장소가 어떤 목적의 저장소인지 간단히 설명합니다.

> [!TIP]
> **예시**
> - 깃허브를 배우는 첫 번째 프로젝트입니다.
> - 나의 코딩 연습용 저장소입니다.

![저장소 설명 입력 예시](/docs/images/step-04-image-06.png)

#### Local Path(로컬 경로)

"Local Path"에서 `Choose...` 버튼을 클릭하여 저장소를 만들 위치를 선택합니다.

![로컬 경로 선택 버튼](/docs/images/step-04-image-07.png)

> [!NOTE]
> 아래 사진처럼 "바탕화면" 폴더를 선택합니다 (다른 폴더를 선택해도 되지만, 이번 시간에는 "바탕화면"에 저장소를 만들겠습니다).
> 
> ![로컬 경로 선택 예시](/docs/images/step-04-image-08.png)

#### 리드미 초기화

"Initialize this repository with a README" 박스를 클릭합니다.

![README 초기화 체크박스](/docs/images/step-04-image-09.png)

> [!TIP]
> **리드미란?**
> 
> 리드미는 우리 저장소에 대해 설명하는 파일입니다. 마치 책의 앞표지처럼, 다른 사람들이 우리 저장소를 이해할 수 있도록 도와줍니다(물론 우리가 리드미에 내용을 작성해야 합니다).

### 4단계: 저장소 만들기

모든 정보를 입력했으면, `Create Repository` 버튼을 클릭합니다.

![Create Repository 버튼](/docs/images/step-04-image-10.png)

그럼 이제 화면이 바뀌며 우리가 만든 "my-first-project" 저장소가 보입니다.

![새로 만든 저장소 화면](/docs/images/step-04-image-11.png)

### 5단계: 깃허브에 저장소 업로드하기

이제 우리 컴퓨터(노트북)에 만든 저장소를 깃허브에 업로드하겠습니다!

깃허브 데스크탑 오른쪽 위에 있는 `Publish repository` 버튼을 클릭합니다.

![Publish repository 버튼](/docs/images/step-04-image-12.png)

새 창이 열리면, "Keep this code private" 박스를 클릭해 체크를 해제하여 다른 사람들이 우리 저장소를 볼 수 있도록 설정합니다. 그리고 `Publish repository` 버튼을 클릭합니다.

![Publish repository 설정 창](/docs/images/step-04-image-13.png)

깃허브에 저장소를 업로드하는 과정을 잠시 기다립니다.

### 6단계: 깃허브에서 확인하기

깃허브 데스크탑에서 위쪽 메뉴의 `Repository`를 클릭합니다.

![Repository 메뉴 클릭](/docs/images/step-04-image-14.png)

`View on GitHub`를 클릭합니다.

![Repository 메뉴에서 View on GitHub 선택](/docs/images/step-04-image-15.png)

웹 브라우저(Microsoft Edge, Chrome 등)가 열리면서 깃허브에 업로드했던 저장소를 확인합니다!

![깃허브에 업로드된 저장소 확인](/docs/images/step-04-image-16.png)

## ✅ 완료!
축하합니다! 🎉 깃허브 데스크탑으로 내 컴퓨터(노트북)에 저장소를 만들고 깃허브에 업로드했습니다!

### 마지막 단계: 만들었던 폴더 제거하기

다음 단계에서 깃허브에 업로드한 저장소를 내 컴퓨터(노트북)로 복제해오는 연습을 하기 위해, 방금 만든 폴더를 제거하겠습니다.

깃허브 데스크탑에서 위쪽 메뉴의 `Repository`를 클릭합니다.

![Repository 메뉴 클릭](/docs/images/step-04-image-14.png)

`Remove...`를 클릭합니다.

![Repository 메뉴에서 Remove 선택](/docs/images/step-04-image-17.png)

아래 사전처럼 "Also move this repository to Recycle Bin" 박스를 클릭해 체크함으로써 내 컴퓨터(노트북)에서 저장소를 완전히 삭제하도록 설정합니다. 그리고 `Remove` 버튼을 클릭합니다.

![Remove 확인 창](/docs/images/step-04-image-18.png)

> [!NOTE]
> **왜 삭제하나요?**
> 방금 우리는 저장소를 깃허브에 업로드했으니 걱정하지 않아도 됩니다. 다음 단계에서 우리는 GitHub에 있는 저장소를 내 컴퓨터로 복제해오는 연습을 합니다.

이제 우리는 **깃**을 설치하고, **깃허브 데스크탑**을 설치하고, **깃허브 계정**을 만들고, **저장소**도 만들어서 **깃허브에 업로드**했습니다!

---

👈 이전: [STEP 03: GitHub Desktop 설치 안내](/docs/step03-github-desktop-installation.md)

👉 다음: [STEP 05: GitHub Desktop으로 저장소 클론](/docs/step05-clone-repository.md)
