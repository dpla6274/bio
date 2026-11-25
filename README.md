# dpla

carrd 프로필을 옮긴 개인 페이지. 파일은 이게 전부:

- `index.html` — 페이지 전체 (MAIN / PROMPT / PAIR, 인덱스 탭, 복사 기능)
- `assets/` — 종이·포스트잇 사진, 네임펜 인덱스 글씨, 형광펜, 폰트

## 올리는 법 (GitHub Pages)

1. GitHub에서 새 저장소 만들기 (Public)
2. 이 폴더 안의 `index.html`, `README.md`, `assets` 폴더를 그대로 업로드 (Add file → Upload files)
3. 저장소 Settings → Pages → Branch: `main` / `(root)` → Save
4. 1~2분 뒤 `https://dpla6274.github.io/저장소이름/` 에서 열림

## 고칠 때

- MAIN 문구: `index.html`의 `<section class="page main">` 안
- 프롬프트 내용: 아래쪽 `<script>`의 `const P = { ... }`
- PAIR 링크: `const PAIR_URL`
- ASK 링크: `<nav class="tabs">`의 ASK 줄
- 형광펜 칠할 문구: `<span class="hl">문구</span>`
