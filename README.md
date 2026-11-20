# GJ Campus & Local

광주·전남 유학생 및 거주 외국인을 위한 정착 가이드 웹 프로토타입 (2차 수정본).

- 단일 파일 프로토타입: `index.html` (빌드 과정 없음)
- 모바일 앱 셸 형태(최대 430px)로 표시되는 정적 페이지
- 외부 의존성: Tailwind CSS CDN, Google Fonts(Inter) — 모두 공개 CDN
- 다국어 선택: 한국어 / English / Tiếng Việt / 中文 / ไทย / Bahasa Indonesia / 日本語 / Oʻzbekcha
- 축제·정보 데이터는 브라우저 저장소(localStorage)에 보관되는 데모용 데이터입니다.

## 로컬에서 보기

`index.html`을 브라우저로 열면 바로 확인할 수 있습니다.

## 관리자(데모)

관리자 화면의 PIN은 데모 값 `1234`입니다. 실제 서비스로 배포하기 전에는
서버 측 인증(Supabase Auth, JWT 등)으로 교체해야 합니다.

## 배포

`index.html`이 루트에 있으므로 GitHub Pages, Vercel, Cloudflare Pages 어디에든
별도 설정 없이 정적 파일로 배포할 수 있습니다.

- GitHub Pages: Settings → Pages → Source `main` / `/ (root)`
