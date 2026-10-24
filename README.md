# Korea Droid Depot

C-25와 아미달라 드레스 조명을 관리하는 Android 앱의 배포 저장소입니다.

[최신 APK 받기](https://github.com/koreadroiddepot/Korea-Droid-Depot-app/releases/latest)

앱 1.2.4부터 **앱 설정 → 앱 업데이트**에서 새 버전을 확인하고 다운로드한 뒤 Android 설치 화면으로 이동할 수 있습니다. 이 기능이 없는 이전 버전에서는 1.2.4 APK를 처음 한 번 설치해 주세요. 기존 앱을 삭제하지 않고 덮어 설치하면 등록된 기기와 설정을 유지합니다.

Android 7.0(API 24) 이상이 필요합니다. 설치 시 Android의 설치 허용과 최종 확인이 필요할 수 있습니다.

`app-latest.json`은 앱 전용 업데이트 정보입니다. C-25 본체의 펌웨어는 별도 [C25-firmware 저장소](https://github.com/koreadroiddepot/C25-firmware)에서 배포합니다.

## 배포 순서

1. 버전 코드를 증가시키고 기존 앱과 같은 인증서로 APK를 서명합니다.
2. 새 릴리스에 APK를 게시하고 공개 파일의 SHA-256과 크기를 검증합니다.
3. 검증한 APK의 버전, URL, SHA-256, 크기로 `app-latest.json`을 갱신합니다.

서명 키, Wi-Fi 비밀번호, 기기 백업과 진단 로그는 이 저장소에 올리지 않습니다.
