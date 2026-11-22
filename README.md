# GeosangManager 공식 배포

Windows 64비트용 GeosangManager 실행 파일과 업데이트 정보를 배포하는 전용 저장소입니다. 소스 코드와 운영 데이터는 포함하지 않습니다.

## 설치

[Releases](https://github.com/jshcry-byte/GeosangManager-Releases/releases)에서 최신 정식 버전의 `GeosangManager-버전-windows-x64.zip`을 다운로드하고 폴더 전체를 풀어 `GeosangManager.exe`를 실행하세요. EXE와 `_internal` 폴더를 분리하지 마세요.

## 업데이트

1.1.0부터 새 버전을 자동 확인합니다. 알림에 동의하면 검증한 파일을 내려받고, 앱을 정상 종료한 뒤 업데이트·재실행합니다. 하단의 업데이트 확인 버튼으로 직접 확인할 수도 있습니다. 이전 버전의 최초 설치는 ZIP으로 진행하세요.

사용자 DB·설정·인증정보는 기존 Windows 사용자 폴더에 유지됩니다. 업데이트 ZIP에 개인 데이터나 인증정보를 넣지 마세요. 관리자 권한이 필요 없는 쓰기 가능한 폴더에서 사용하세요.

`update-windows-x64.json`은 앱의 버전·파일 크기·SHA-256 확인용 정보입니다. 앱은 공개 GitHub 다운로드에 사용자 인증정보를 전송하지 않습니다.
