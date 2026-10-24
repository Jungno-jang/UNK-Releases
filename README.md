# UNK 프로그램 다운로드

UNK Launcher, UNK Excel, UNK Film, UNK PDF의 Windows 설치 파일과 서명된 업데이트 정보를 제공합니다.

설치 파일은 [Releases](https://github.com/Jungno-jang/UNK-Releases/releases)에서 내려받으세요.
[UNK Launcher 0.2.1 시험 배포](https://github.com/Jungno-jang/UNK-Releases/releases/tag/launcher-0.2.1)에서 런처 설치 파일을 받을 수 있습니다.
GitHub 로그인 없이 다운로드할 수 있습니다. Windows 10/11 x64용입니다.

런처는 설치된 프로그램의 새 배포본을 실행 시와 15분마다 확인합니다.
서명과 파일 해시가 일치하는 배포본만 사용하며, 실행 중인 앱은 종료 후 업데이트합니다.
자동 업데이트와 트레이 실행은 런처 설정에서 끌 수 있습니다.
처음 프로그램을 설치할 때 바탕화면 바로가기 선택을 제공하며 기본값은 생성입니다. 업데이트에서는 기존 선택을 유지합니다.

개발 저장소는 별도로 관리합니다. 각 프로그램에 동봉된 오픈소스 라이선스와 고지가 적용됩니다.
UNK PDF는 AGPL-3.0-or-later에 따른 해당 버전 소스와 빌드 자료를 함께 제공합니다.
PDF 소스 공개는 사용자 개인 PDF 문서나 설정 공개를 뜻하지 않습니다.

실행 파일에는 Windows Authenticode 인증서가 적용되어 있지 않습니다.
업데이트 정보의 Ed25519 서명은 Windows 코드 서명과 별개입니다.

`stable.json`과 `stable.json.sig`는 런처용 배포 정보입니다. 직접 수정하면 서명 검증에 실패합니다.
