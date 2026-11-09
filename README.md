# 통암기

본문 통암기용 웹앱. GitHub Pages에 올려 아이패드 홈 화면에 추가해서 쓴다.

## 올리기
1. GitHub에서 새 저장소 생성 (예: `tongamgi`, Public)
2. 이 폴더의 파일 전부(index.html, sw.js, manifest.webmanifest, icon-*.png)를 저장소 루트에 업로드
3. Settings → Pages → Branch `main` / `(root)` → Save
4. 1~2분 뒤 `https://<아이디>.github.io/tongamgi/` 접속
5. 아이패드 Safari → 공유 → 홈 화면에 추가

## 수정 후 반영
파일을 덮어쓰고 커밋하면 다음 실행 때 자동 반영된다(오프라인에서도 열림).

## 본문 추가
- 앱 안에서: 첫 화면 `+` → 제목·본문 붙여넣기 (그 기기에만 저장)
- 모든 기기 공통으로: `index.html`의 `BUILTIN` 배열에 `{id, title, lines:[...]}` 추가
