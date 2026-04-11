# STEP 06: 내 컴퓨터에서 파일 수정 또는 생성하기 (macOS)

## 🎯 이 단계에서 배우는 것
내 컴퓨터에 있는 저장소(Repository) 파일을 직접 수정하거나 새로 만드는 방법입니다. 파일을 바꾸면 깃허브 데스크탑(GitHub Desktop)에서 어떤 내용이 변경되었는지도 함께 확인할 수 있습니다.

## 📂 파일 수정 또는 생성하기

### 1단계: 파일 열기

깃허브로부터 복제해온 저장소(폴더)를 Finder(파인더)에서 찾습니다.

![Finder 열기](/docs/images/macos/step-06-image-01.png)

Finder 창이 열리면, 오른쪽 위 돋보기 버튼을 클릭합니다.

![돋보기 버튼](/docs/images/macos/step-06-image-02.png)

검색창에 "my-first-project"를 입력하고 `my-first-project` 폴더를 찾아 더블클릭합니다.

![폴더 이미지](/docs/images/macos/step-06-image-03.png)

폴더 안에 있는 README.md 파일을 우클릭(또는 트랙패드 두 손가락 클릭) 후, `다음으로 열기`에 마우스를 올린 후 `텍스트 편집기`를 클릭합니다.

![다음으로 열기 메뉴](/docs/images/macos/step-06-image-04.png)

### 2단계: 파일 편집

"텍스트 편집기"를 클릭하면 다음과 같이 파일이 열립니다. 단계를 잘 따라왔다면, 아래 사진처럼 기존에 텍스트가 이미 존재합니다.

![파일 열린 화면](/docs/images/macos/step-06-image-05.png)

이미 존재하는 텍스트들을 모두 지우고, 아래 예시를 활용해 자신에 대한 내용으로 바꿔봅니다.

> [!NOTE]
> **예제**
> 
> ```markdown
> 이름: 깃허브
> 학교: 깃허브학교
> 잘하는 일: 깃허브로 협업하기
> ```

그럼 이제 다음과 같은 내용만 남습니다.

![파일 편집된 화면](/docs/images/macos/step-06-image-06.png)

## 변경 사항 확인

`command + S`를 눌러 수정한 내용을 저장하면, 깃허브 데스크탑이 변경한 파일을 자동으로 감지해 내가 어떤 파일을 수정했는지 보여줍니다. 아래 단계를 따라 변경 사항을 확인해봅니다 :

`command + 스페이스바`를 눌러 검색창을 열고, "GitHub Desktop"을 입력한 후 엔터를 눌러 깃허브 데스크탑을 실행합니다.

![깃허브 데스크탑 검색](/docs/images/macos/step-06-image-07.png)

깃허브 데스크탑을 열면, 왼쪽 위에 내가 선택한 저장소 이름이 `my-first-project`로 나타나는 지 확인합니다.

> [!NOTE]
> 만약 저장소의 이름이 `my-first-project`가 아니라면 `Current Repository`를 클릭한 후 `my-first-project`를 선택합니다.

![저장소 선택](/docs/images/macos/step-06-image-08.png)

아래 사진처럼 내가 제거한 내용과 새로 작성한 내용을 각각 빨간색과 초록색으로 확인할 수 있습니다.

![변경 사항 확인](/docs/images/macos/step-06-image-09.png)


## ✅ 완료!
축하합니다! 🎉 내 컴퓨터 속 저장소에서 파일을 직접 수정하는 작업을 성공적으로 해냈습니다!

이제 우리는 내 컴퓨터에서 프로젝트 파일을 편집하는 방법을 익혔고, 파일을 저장하면 깃허브 데스크탑이 변경 내용을 자동으로 보여준다는 것도 확인했습니다.

다음 단계에서는 이렇게 수정한 내용에 대한 세이브 포인트를 만들고 깃허브에 업로드하는 방법을 배워봅니다.

---

👈 이전: [STEP 05: 깃허브 데스크탑으로 저장소 클론하기](/docs/macos/step05-clone-repository.md)

👉 다음: [STEP 07: 깃허브 데스크탑에서 커밋 후 푸시하기](/docs/macos/step07-local-commit-push.md)
