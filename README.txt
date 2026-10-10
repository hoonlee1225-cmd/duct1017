# 국소배기 필요환기량 계산기

## GitHub Pages 배포
1. GitHub에서 새 **Public** repository를 만듭니다. 예: `ventilation-calculator`
2. 이 ZIP 파일의 압축을 풉니다.
3. 저장소의 **Add file → Upload files**로 압축 해제한 파일 5개를 업로드합니다.
4. **Commit changes**를 누릅니다.
5. 저장소의 **Settings → Pages**로 이동합니다.
6. **Build and deployment → Source**에서 `Deploy from a branch`를 선택합니다.
7. Branch는 `main`, folder는 `/(root)`로 설정하고 **Save**를 누릅니다.
8. 잠시 기다린 후 Settings → Pages에 나타나는 사이트 주소를 엽니다.

예상 주소 형식: `https://YOUR-USERNAME.github.io/ventilation-calculator/`

## 스마트폰에 설치
Android Chrome에서 배포된 주소를 엽니다. 메뉴(⋮)에서 **앱 설치** 또는 **홈 화면에 추가**를 선택합니다.

## 포함 파일
- `index.html`: 계산기 본체
- `manifest.json`: PWA 설치 설정
- `service-worker.js`: 오프라인 캐시
- `icon-192.png`, `icon-512.png`: 앱 아이콘

## 주의
GitHub Free에서는 Pages 배포용 저장소를 Public으로 설정해야 합니다. 사이트는 인터넷에 공개되므로 개인정보나 비밀 자료를 업로드하지 마세요. 계산 결과는 공식의 적용 조건 및 단위 환산을 원본 기준과 대조한 뒤 실제 설계에 사용하세요.
