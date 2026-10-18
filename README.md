# 냠냠! 동물 식당 (v1.0)

26개월 전후 아이를 위한 동물 먹이주기 놀이입니다. 공개 가능한 게임 코드만 저장하며 부모 녹음, 사진, 아이 이름, 계정 정보는 포함하지 않습니다.

## 게임 열기
GitHub Pages를 활성화하면 주소는 https://donggeun-kr.github.io/nyam-animal-diner/ 입니다.
설정: Settings → Pages → Build and deployment → Source **Deploy from a branch** → Branch **main** / **(root)** → Save.

갤럭시 크롬에서 게임 링크를 연 뒤 메뉴에서 '홈 화면에 추가'를 선택하면 아이콘으로 실행할 수 있습니다.

## 파일
- `index.html`: 설치 없이 실행하는 게임 본체
- `icon.svg`, `manifest.webmanifest`: 홈 화면 앱 이름 및 아이콘
- `.github/workflows/ci.yml`: 저장소 변경 시 웹 자산 검사

## 관리 원칙
- 개발: ChatGPT, 사용자 승인 후 게시. 향후 기능 수정은 이슈 → 변경 브랜치 → PR 검토 → CI 통과 → 승인 후 main 병합.
- 공개 저장소에 개인 정보 및 가족 녹음 파일 추가 금지.
- 이 사이트는 별도 백엔드가 없으며, 기본 음성은 기기의 TTS를 사용합니다.
