# 틈 캘린더

휴대폰 홈 화면에 설치해서 쓰는 일정 앱(PWA)이에요. 서버가 필요 없고, 일정은 각 기기에 저장돼요.

## 파일
- `index.html` 앱 본체
- `manifest.webmanifest` 앱 이름·아이콘·전체 화면 설정
- `sw.js` 오프라인에서도 열리게 하는 캐시
- `icon-*.png`, `apple-touch-icon.png` 홈 화면 아이콘

## GitHub Pages로 올리기 (무료, 약 5분)
1. github.com 가입 후 오른쪽 위 **+ → New repository**. 이름은 `teum`, **Public** 선택 후 Create.
2. 저장소 화면에서 **uploading an existing file**을 눌러 이 폴더의 파일 7개를 모두 끌어다 놓고 **Commit changes**.
3. **Settings → Pages**에서 Source를 **Deploy from a branch**, Branch를 **main / (root)**로 두고 Save.
4. 1~2분 뒤 `https://내아이디.github.io/teum/` 주소가 생겨요.

## 휴대폰에 설치
- 아이폰: Safari로 위 주소 열기 → 공유 버튼 → **홈 화면에 추가**
- 안드로이드: Chrome으로 열기 → ⋮ → **앱 설치** 또는 **홈 화면에 추가**

## 업데이트
파일을 고친 뒤 같은 저장소에 다시 올리면, 앱을 다음에 열 때 새 버전이 반영돼요.

## 다른 기기로 일정 옮기기
앱 맨 아래 **백업 내보내기**로 파일을 저장하고, 다른 기기에서 **백업 가져오기**로 불러와요.
