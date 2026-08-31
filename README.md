# 개인정보처리방침 모음

handfirst 가 만든 앱·확장 프로그램의 개인정보처리방침을 한곳에 모아 GitHub Pages 로 게시한다.
스토어 심사에 제출하는 공개 URL 이므로 **주소가 바뀌면 안 된다.**

공개 주소: https://handfirst2025.github.io/privacy/

## 구조

앱 하나당 디렉터리 하나. 디렉터리 이름이 곧 URL 이다.

```
index.html            허브 — 앱 목록
recordmeet/index.html RecordMeet  (Chrome 웹스토어)
tigerdocu/index.html  TigerDocu   (Google Play)
```

| 앱 | 제출용 URL |
|---|---|
| RecordMeet | https://handfirst2025.github.io/privacy/recordmeet/ |
| TigerDocu | https://handfirst2025.github.io/privacy/tigerdocu/ |

## 앱 추가하기

1. `<앱이름>/index.html` 생성 — 기존 파일을 복사해 `--accent` 색과 본문만 바꾼다.
   각 페이지는 인라인 CSS 만 쓰는 단일 파일이다. 빌드 도구나 의존성이 없다.
2. 맨 위에 `<a class="back" href="../">← 전체 목록</a>` 를 남겨 둔다.
3. 루트 `index.html` 의 `.list` 안에 카드 한 줄을 추가한다.
4. push 하면 몇십 초 뒤 Pages 에 반영된다.

## 주의

- **리포지터리 이름을 바꾸지 말 것.** rename 하면 Pages 주소가 같이 바뀌고
  옛 주소는 리다이렉트되지 않는다. 스토어에 등록해 둔 링크가 죽는다.
- 같은 이유로 디렉터리 이름도 한 번 제출한 뒤에는 바꾸지 않는다.
- 방침을 고칠 때는 본문의 시행일과 최종 수정일을 함께 갱신한다.

## 기존 리포지터리

`handfirst2025/tigerdocu-privacy` 는 그대로 살려 둔다.
구글 플레이에 등록된 링크가 아직 그쪽을 가리키고 있어, 지우면 심사 링크가 끊긴다.
플레이 콘솔의 URL 을 이 리포로 바꾼 뒤에 정리한다.
