# GeosangManager 공식 배포

Windows 64비트용 GeosangManager 실행 파일과 업데이트 정보를 배포하는 전용 저장소입니다. 소스 코드와 운영 데이터는 포함하지 않습니다.

## 설치

[최신 릴리즈](https://github.com/jshcry-byte/GeosangManager-Releases/releases/latest)에서 **GeosangManager-버전-Setup.exe**를 다운로드해 실행하세요. 1.1.1은 전체 설치본이므로 1.1.0을 먼저 설치할 필요가 없습니다. 기존 앱은 정상 종료한 뒤 설치하세요.

관리자 권한 없이 현재 사용자용 `%LOCALAPPDATA%\Programs\GeosangManager`에 설치하며 시작 메뉴·선택형 바탕화면 바로가기·Windows 프로그램 제거 기능을 제공합니다. 설치·제거 시 기존 사용자 DB·설정·인증정보는 삭제하지 않습니다. 설치 파일은 현재 코드 서명되지 않았습니다.

## 업데이트

1.1.0부터 새 버전을 자동 확인합니다. 알림에 동의하면 검증한 파일을 내려받고, 앱을 정상 종료한 뒤 업데이트·재실행합니다. 하단의 업데이트 확인 버튼으로 직접 확인할 수도 있습니다. 설치형 클라이언트는 이후 업데이트에 설치 프로그램을 우선 사용합니다.

ZIP은 1.1.0 업데이터와의 호환용으로 함께 제공합니다. 1.1.0에서 ZIP 업데이트만 받으면 설치 등록이 생기지 않으므로, 설치형으로 전환할 때 Setup.exe를 한 번 실행하세요.

사용자 DB·설정·인증정보는 기존 Windows 사용자 폴더에 유지됩니다. 배포 파일에 개인 데이터나 인증정보를 넣지 마세요.

`update-windows-x64.json`은 앱의 버전·파일 크기·SHA-256 확인용 정보입니다. 앱은 공개 GitHub 다운로드에 사용자 인증정보를 전송하지 않습니다.

## 사용자 매뉴얼

- [PC 인증 자세히 따라하기](manuals/사용자매뉴얼.md#0-pc-인증-따라하기): 최초 등록·초대 코드·승인 수령·PC 교체·재신청·등록 해제를 실제 앱 캡처 13장과 함께 설명합니다.
- [전체 사용자 매뉴얼](manuals/사용자매뉴얼.md): PC 인증과 기존 정령탐색 사용법입니다.
- [오프라인 열람용 매뉴얼 ZIP](https://github.com/jshcry-byte/GeosangManager-Releases/releases/download/v1.1.1/GeosangManager-1.1.1-User-Manual.zip): 압축을 풀고 MD 파일과 images 폴더를 함께 보관하세요.

캡처는 예시 이름과 합성 응답을 사용했으며 실제 사용자의 인증정보를 포함하지 않습니다.
