# 도요새편지 2026년 9월호 (창간호)

(사)박원순혁신재단 회원 소식지 웹 버전입니다.

## 파일 구성

```
index.html          ← 소식지 본문 (26KB)
assets/cover.mp4    ← 표지 영상
assets/poster.jpg   ← 표지 영상이 뜨기 전 보이는 첫 화면
assets/photo.jpg    ← 회원의날 단체사진
.nojekyll           ← 빈 파일 (직접 만들어 추가)
README.md           ← 이 문서
```

`index.html`은 반드시 저장소 최상단에, 나머지 세 파일은 `assets` 폴더 안에 그대로 두어야 합니다. 폴더 이름이나 파일 이름을 바꾸면 사진과 영상이 나오지 않습니다.

## 배포 방법

1. GitHub에서 새 저장소를 만듭니다. (공개 저장소여야 Pages를 무료로 쓸 수 있습니다)
2. `index.html`과 `README.md`를 최상단에 올립니다.
3. `assets` 폴더째로 올립니다. 웹에서 올릴 때는 Add file → Upload files 화면에 폴더를 그대로 끌어다 놓으면 됩니다.
4. Add file → Create new file을 누르고 이름 칸에 `.nojekyll`만 입력한 뒤 내용 없이 저장합니다.
5. Settings → Pages에서 Source를 `Deploy from a branch`, Branch를 `main` / `/ (root)`로 두고 Save합니다.
6. 1~2분 뒤 주소가 열립니다.

## 다음 호 올릴 때

호차별 폴더로 쌓으면 지난 호 링크가 계속 살아 있습니다.

```
/2026-09/index.html + /2026-09/assets/
/2026-10/index.html + /2026-10/assets/
```

## 참고

- 본문 글꼴은 Google Fonts에서 불러옵니다. 인터넷이 연결된 환경에서 열어야 의도한 서체로 보입니다.
- 표지 영상은 소리 없이 자동 반복 재생됩니다. 기기가 저전력 모드이면 자동재생이 막힐 수 있고, 이때는 화면을 한 번 누르면 재생됩니다.
