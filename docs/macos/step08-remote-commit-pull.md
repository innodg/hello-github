# STEP 08: 원격 저장소에서 깃허브 변경 내용 가져오기 (macOS)

## 🎯 이 단계에서 배우는 것
깃허브(GitHub)에서 수정한 내용을 내 컴퓨터로 가져오는 방법입니다. 풀(Pull)을 하면 원격 저장소(Repository)에서 바뀐 내용을 내 컴퓨터에도 반영할 수 있습니다.

## 📚 풀(Pull)이 뭔가요?

풀(Pull)은 앞서 이야기했던 깃허브(GitHub)의 원격 저장소(Repository)에 있는 최신 변경 내용을 내 컴퓨터로 가져오는 작업입니다.

## 🔽 깃허브에서 수정하고 풀하기

### 1단계: 깃허브 웹사이트 접속

아래 사진처럼 웹 브라우저(Microsoft Edge, Chrome 등) 주소창에 [STEP 07의 3단계: 저장소 확인](/docs/macos/step07-local-commit-push.md#3단계-저장소-확인) 부분 마지막에 복사해둔 주소를 주소창에 입력한 뒤 접속합니다.

![웹 브라우저 주소창에 저장소 주소 입력](/docs/images/macos/step-07-image-14.png)

### 2단계: 수정할 파일 선택

수정하고 싶은 파일을 클릭합니다. 지금은 `README.md` 파일을 선택할 것입니다.

![README.md 파일 선택](/docs/images/macos/step-08-image-01.png)

### 3단계: 파일 수정하기

아래 사진 속 위치(오른쪽 위)의 연필 모양 아이콘을 클릭합니다.

![파일 수정 버튼](/docs/images/macos/step-08-image-02.png)

파일 내용을 원하는 대로 수정합니다.

![파일 수정 화면](/docs/images/macos/step-08-image-03.png)

### 4단계: 웹에서 커밋하기

수정이 끝나면 `Commit changes...` 버튼을 클릭합니다.

![Commit changes 버튼](/docs/images/macos/step-08-image-04.png)

커밋 메시지를 수정하고 싶다면 `Commit message(제목)` 입력란과 `Extended description(본문)` 입력란에 내용을 작성합니다. 이번에는 아무것도 건드리지 않고 곧바로 `Commit changes` 버튼을 클릭하겠습니다.

![커밋 메시지 작성](/docs/images/macos/step-08-image-05.png)

### 5단계: 깃허브 데스크탑으로 돌아오기

깃허브 데스크탑 화면으로 돌아옵니다.

> [!TIP]
> 만약 깃허브 데스크탑을 실행 중이지 않다면, `command + 스페이스 바`를 눌러 검색창을 열고 "GitHub Desktop"을 검색한 후 Enter 키를 눌러 실행합니다.

> [!NOTE]
> 깃허브 데스크탑 화면에서 현재 선택한 저장소가 "my-first-project"인지 확인합니다.
>
> ![저장소명 체크](/docs/images/macos/step-05-image-04.png)

### 6단계: 풀 버튼 클릭

아래 사진 속 빨간 네모 부분에 있는 `Pull origin` 버튼을 클릭합니다.

> [!TIP]
> 만약 글씨가 `Pull origin`이 아니라 `Fetch origin`으로 보인다면, 동일한 위치에 있는 `Fetch origin` 버튼을 클릭한 뒤 다시 `Pull origin` 버튼이 나타나는지 확인해봅니다.

![Pull origin 버튼](/docs/images/macos/step-08-image-06.png)

아래 사진처럼 왼쪽에 위치한 `History`을 통해 내 컴퓨터에서 변경 사항을 확인할 수 있습니다.

![History 탭 확인](/docs/images/macos/step-08-image-07.png)

## ✅ 완료!
축하합니다! 🎉 깃허브 웹사이트에서 수정한 내용을 커밋하고, 깃허브 데스크탑을 이용해 내 컴퓨터로 성공적으로 가져왔습니다.

이제 우리는 깃허브 웹사이트에서 파일을 수정한 뒤, 커밋으로 변경 내용을 기록하고, 풀을 통해 그 내용을 내 컴퓨터에 반영하는 흐름까지 완성했습니다.

다음 단계에서는 이슈(Issue)를 생성하면서, 해야 할 일이나 수정할 내용을 깃허브에서 정리하고 관리하는 방법을 배워볼 예정입니다.

---

👈 이전: [STEP 07: GitHub Desktop에서 커밋 후 푸시하기](/docs/macos/step07-local-commit-push.md)

👉 다음: [STEP 09: 이슈 생성하기](/docs/step09-create-issue.md)
