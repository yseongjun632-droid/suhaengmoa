# 수행모아
수행평가 일정관리 PWA. GitHub Pages에 배포할 수 있습니다.

## 배포
1. GitHub에서 Public repository 생성
2. 이 폴더의 파일을 repository root에 업로드
3. Settings → Pages → Deploy from a branch → main / root 저장
4. 생성된 `https://USERNAME.github.io/REPOSITORY/` 주소를 모바일에서 방문
5. Android Chrome: 메뉴 → 앱 설치/홈 화면에 추가
6. iOS Safari: 공유 → 홈 화면에 추가

## 데이터
수행평가 텍스트는 localStorage, 첨부파일은 IndexedDB에 기기별로 저장됩니다. 서버로 전송되지 않으며 기기 간 자동 동기화되지 않습니다. 파일 공유는 기기의 OS 공유 메뉴를 호출합니다.
