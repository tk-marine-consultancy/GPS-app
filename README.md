# GPS Speed & Bearing PWA

실시간 GPS 속력(노트) · 방향(방위각) 측정 앱

## GitHub Pages 배포 방법

1. GitHub에서 새 저장소 생성 (예: `gps-speed-app`)
2. 이 폴더의 파일 4개를 모두 업로드:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
3. Settings → Pages → Branch: main → Save
4. 약 1분 후 접속: `https://[아이디].github.io/gps-speed-app`

## 홈화면에 앱으로 설치 (Android)

1. Chrome으로 위 URL 접속
2. 주소창 오른쪽 ⋮ 메뉴 → **"앱 설치"** 또는 **"홈 화면에 추가"**
3. 바탕화면에서 앱 아이콘으로 실행 ✅

## 기능

- 실시간 속력 (노트, 소수점 1자리)
- 진행 방향 (0~360°, 16방위 표시)
- 회전 나침반 UI
- 수동 Heading 입력
- 누적 이동 거리
- GPS 정확도 표시 (30m 초과시 데이터 무시)
- 오프라인 캐시 (Service Worker)
- 전체화면 앱 모드
