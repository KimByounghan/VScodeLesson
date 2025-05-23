좋습니다. 사용 중인 확장 프로그램 **Markdown All in One**은 VSCode에서 마크다운(Markdown) 문서를 보다 편리하게 작성하고, 실시간 미리보기를 하며, 자동 목차 등 기능을 활용할 수 있게 해주는 확장입니다.

아래에 사용법을 차근차근 안내드리겠습니다.

---

## 🟦 1. 마크다운 파일 만들기

1. VSCode에서 `파일 → 새 파일` 선택

2. 아래처럼 파일 내용 작성:

   ```markdown
   # 나의 마크다운 문서

   ## 소개
   이것은 Markdown All in One 확장으로 작성한 문서입니다.

   - 항목 1
   - 항목 2

   **굵은 글씨**, *기울임 글씨*도 됩니다.
   ```

3. `Ctrl + S`로 저장 → 파일 이름을 `example.md`로 저장합니다. (`.md` 확장자 필수)

---

## 🟦 2. 미리보기 보기

* 우측 상단 또는 에디터 탭 위에서 `마우스 오른쪽 클릭 → Markdown 미리 보기 열기` 선택
  또는 단축키: `Ctrl + K V`
* 화면 오른쪽에 미리보기 창이 열리면서 실시간으로 편집 내용이 반영됩니다.

---

## 🟦 3. 자동 목차 생성 (Table of Contents)

문서 상단에 아래와 같이 입력하면, 자동으로 목차가 생성됩니다:

```markdown
<!-- TOC -->
<!-- /TOC -->
```

→ 저장 시 문서 내의 모든 제목(`#, ##`)이 자동으로 링크로 된 목차로 채워집니다.

---

## 🟦 4. 기타 유용한 단축키

| 기능       | 단축키                  |
| -------- | -------------------- |
| 굵게       | `Ctrl + B`           |
| 기울임      | `Ctrl + I`           |
| 목록 만들기   | `-` 또는 `*` 입력 후 스페이스 |
| 코드 블록    | 백틱(\`) 세 개를 입력       |
| 자동 목차 갱신 | 저장하면 자동으로 갱신됨        |

---

## 🟦 5. 자동 완성과 미리보기 설정 (선택)

만약 자동 완성이 안 되는 경우:

1. `파일 → 기본 설정 → 설정` 이동
2. 검색창에 `markdown` 입력
3. 필요한 옵션(자동 미리보기, 단축키 등)을 켤 수 있습니다.

---

## ✅ 요약

* `.md` 파일을 만들고 저장
* `Ctrl + K V`로 미리보기 확인
* `<!-- TOC -->`로 목차 자동 생성
* 단축키를 활용한 빠른 편집 가능

---

원하시면 마크다운을 활용해 블로그 글, README 파일, 또는 강의 노트도 작성해보실 수 있습니다.
예시 파일이 필요하시면 만들어드릴까요?
