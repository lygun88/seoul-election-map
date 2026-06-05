# 서울시 행정동별 1위 후보 득표율 지도

GitHub Pages 업로드용 정적 사이트입니다.

## 업로드 방법

1. GitHub에서 새 Repository를 만듭니다. 예: `seoul-election-map`
2. 이 폴더 안의 파일을 Repository 루트에 업로드합니다.
   - `index.html`
   - `.nojekyll`
   - `assets/` 폴더
3. Repository > Settings > Pages로 이동합니다.
4. Source를 `Deploy from a branch`로 선택합니다.
5. Branch는 `main`, Folder는 `/ (root)`로 선택 후 Save합니다.
6. 잠시 뒤 `https://<GitHub아이디>.github.io/seoul-election-map/` 형태의 URL로 접속합니다.

## 참고

- `index.html`이 메인 화면입니다.
- 모바일에서 URL을 열면 바로 지도가 표시됩니다.
- 실제 행정동 경계는 외부 GeoJSON과 D3 CDN을 불러옵니다. 따라서 접속 환경에서 인터넷 연결이 필요합니다.
