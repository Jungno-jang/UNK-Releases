# UNK 프로그램 다운로드

오픈소스를 기반으로 제작한 **UNK Sheet·UNK Film·UNK PDF를 편하게 설치하고 업데이트하기 위한 UNK Launcher 배포 페이지**입니다. Windows 10/11 x64용 설치 파일과 서명된 업데이트 정보를 제공합니다.

UNK는 이 프로그램들을 **비상업적 목적으로 제작·이용하며 무료로 배포**합니다. 이 안내는 배포자의 목적에 관한 설명이며, 각 오픈소스 및 Microsoft 구성요소의 라이선스와 이용 권리를 변경하지 않습니다.

## 다운로드

| 프로그램 | 설치 파일·고지 사항 |
|---|---|
| UNK Launcher 0.8.0 | [런처 다운로드](https://github.com/Jungno-jang/UNK-Releases/releases/tag/launcher-0.8.0) |
| UNK Sheet 1.0.1 (이전 이름: UNK Excel) | [설치 파일·Microsoft 런타임 조건](https://github.com/Jungno-jang/UNK-Releases/releases/tag/sheet-1.0.1) |
| UNK Film 1.1.2 | [설치 파일·라이선스 고지·런타임 조건](https://github.com/Jungno-jang/UNK-Releases/releases/tag/film-1.1.2) |
| UNK PDF 3.8.2 | [설치 파일·대응 소스 및 빌드 자료](https://github.com/Jungno-jang/UNK-Releases/releases/tag/pdf-3.8.2) |

GitHub 로그인 없이 [Releases](https://github.com/Jungno-jang/UNK-Releases/releases)에서 다운로드할 수 있습니다.

## 설치와 업데이트

자동 확인을 켜면 실행 시와 15분마다 설치된 프로그램의 새 배포본을 확인합니다. 서명과 파일 해시를 검증하며, 실행 중인 앱은 종료 후 업데이트합니다. 자동 업데이트는 상단 ON/OFF 토글로 선택할 수 있고 자동 확인·알림·트레이 실행은 설정에서 선택합니다.

처음 설치할 때 바탕화면 바로가기 생성 여부를 선택하며 기본값은 생성입니다. 업데이트에서는 기존 선택을 유지합니다. Sheet는 기존 UNK Excel 설치 폴더와 설정 식별자를 호환성을 위해 유지하므로 폴더 이름이 예전 이름이어도 중복 설치가 아닙니다.

Sheet·Film의 Microsoft 런타임 조건에 동의가 필요한 경우 전문을 제시합니다. 사용자가 동의하기 전 자동 설치하지 않으며, 동일한 조건의 확인된 동의는 재사용합니다.

## 라이선스와 소스 제공

각 다운로드·설치 파일에 동봉된 LICENSE, NOTICE, 저작권 고지와 해당 구성요소의 조건이 적용됩니다. Sheet 설치 파일은 LICENSE-MIT·LICENSE-APACHE·ATTRIBUTION.md·NOTICE 등을 포함하고, Film 설치 파일은 오픈소스·글꼴·저작권 고지와 Microsoft 런타임 조건을 포함합니다.

UNK PDF는 AGPL-3.0-or-later에 따른 해당 버전의 대응 소스와 빌드 자료를 함께 제공합니다. Film 1.1.2에 포함된 변경 없는 MPL 의존성 13개의 대응 소스는 [공개 소스 제공 자료](https://github.com/Jungno-jang/UNK-Releases/releases/download/film-1.1.1/UNK-Film-MPL-Sources-1.1.1.zip)에서 받으세요. 개발 저장소는 별도로 관리하며, 소스 제공은 사용자의 개인 문서나 설정 공개를 의미하지 않습니다.

실행 파일은 Windows Authenticode 미서명입니다. 업데이트 정보의 Ed25519 서명과 SHA-256 검증은 Windows 코드 서명과 별개입니다.

## 업데이트 정보

런처 0.8.0부터 앱 배포 정보는 `stable-v2.json`과 `stable-v2.json.sig`를 사용합니다. 이전 런처의 호환성을 위해 `stable.json`과 그 서명은 유지합니다. 먼저 런처를 업데이트하면 새 앱 채널의 Sheet·Film 배포본을 확인할 수 있습니다.

런처 자체 업데이트는 `launcher.json`과 `launcher.json.sig`를 사용합니다. 0.2.x 사용자는 최신 런처 설치 파일을 한 번 직접 실행해야 합니다. 서명된 파일을 임의로 수정하면 검증에 실패합니다.
