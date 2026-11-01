# yweb-ads

[Y웹](https://github.com/dusdk0098-tech/YWeb) 홈에 보이는 개발자 광고 피드입니다. 형식과 규칙은 YWeb의 `docs/ADS.md`를 보세요.

- `ads.json`: 광고 목록 (최대 20개, 64KB 이하)
- 이미지: `ads.json` 옆에 `이름.png/.jpg` (300KB 이하)

피드 주소: https://dusdk0098-tech.github.io/yweb-ads/ads.json

## 관리 페이지

https://dusdk0098-tech.github.io/yweb-ads/admin.html 에서 광고를 폼으로 추가·수정·삭제하고 `main`에 바로 커밋합니다(서버 없음, 브라우저 → GitHub API).

토큰 만들기(한 번): GitHub → Settings → Developer settings → Personal access tokens → **Fine-grained tokens** → Generate new token → Repository access: **Only select repositories → yweb-ads** → Permissions → Repository permissions → **Contents: Read and write** → Generate. 관리 페이지의 토큰 칸에 붙여 넣고 "토큰 저장"을 누릅니다. 토큰은 브라우저(기본은 현재 탭)에만 남고 api.github.com 외에는 보내지 않습니다. 토큰 없이도 "JSON 복사"로 결과를 받아 GitHub 웹에서 `ads.json`에 직접 붙여 넣을 수 있습니다.
