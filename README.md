# BBLOG

[한국어](#한국어) · [English](#english)

## 한국어

BBLOG는 FGO(Fate/Grand Order)의 스토리를 한국어 또는 영어로 감상할 수 있게 도와주는 안드로이드 앱입니다.

### 주요 기능

- **스토리 뷰어**: 이벤트, 메인 스토리, 서번트 막간의 이야기 챕터를 골라 앱 안에서 바로 읽을 수 있습니다.
  - 한국어 모드에서는 한국 서버에 정식 출시된 스토리의 공식 한국어 번역을 우선 사용합니다.
  - 영어 모드에서는 북미 서버에 정식 출시된 스토리의 공식 영어 번역을 우선 사용합니다.
  - 선택한 언어로 아직 정식 출시되지 않은 스토리는 AI로 번역할 수 있습니다.
- **번역 직접 수정**: AI 번역이 어색하면 뷰어에서 번역 대사나 이름표를 길게 눌러 직접 수정할 수 있습니다. 같은 화자의 이름표는 해당 챕터 전체에 함께 적용됩니다.
- **게임 화면 위 실시간 오버레이**: 일본 서버에서 직접 플레이하면서 게임 화면 위에 번역 자막을 띄울 수 있습니다. 대사창을 자동으로 인식해 다음 줄로 진행합니다.
- **커뮤니티 번역 공유**: 다른 사용자가 공유한 한국어·영어 번역을 가져와 바로 읽거나, 자신의 번역을 공유할 수 있습니다.
- **한국어·영어 UI 지원**: 설정에서 언어를 바꾸면 앱 UI, 스토리 정보, 뷰어 번역과 생성형 닉네임이 선택한 언어에 맞춰 표시됩니다.
- **가이드 투어**: 최초 설정과 뷰어의 주요 기능을 화면 하이라이트로 안내합니다.

### 설치 방법

1. [Releases](../../releases)에서 최신 APK를 다운로드합니다.
2. Android에서 "출처를 알 수 없는 앱 설치"를 허용합니다.
3. 설치 후 첫 실행 튜토리얼을 따라 필요한 권한과 설정을 완료합니다.

### 참고

- AI 번역에는 본인의 API 키가 필요합니다. Google Gemini, OpenAI, Claude를 지원하며, 키는 튜토리얼 또는 설정에서 등록할 수 있습니다. 사용량에 따라 비용이 발생할 수 있습니다.
- API 키가 없어도 공식 번역이나 이미 저장·공유된 번역은 읽을 수 있습니다.
- 오버레이 자동 대사 인식은 Android 14 QPR2 이상에서 지원됩니다. 이전 버전에서도 오버레이와 수동 이전/다음 조작은 사용할 수 있습니다.
- 이 저장소는 설치 파일 배포 전용입니다.

---

## English

BBLOG is an Android app for reading Fate/Grand Order stories in Korean or English.

### Features

- **Story viewer**: Choose an event, Main Story, or Servant Interlude chapter and read it directly in the app.
  - In Korean mode, BBLOG prioritizes the official Korean localization for stories released on the Korean server.
  - In English mode, BBLOG prioritizes the official North American localization for stories released on the NA server.
  - Stories not yet officially released in the selected language can be translated with AI.
- **Edit AI translations**: Long-press a translated dialogue line or speaker nameplate to correct it. Renaming a speaker updates matching nameplates throughout the chapter.
- **Live in-game overlay**: Display translated subtitles over the Japanese version of FGO while playing. Automatic dialogue detection can advance the subtitle to the matching line.
- **Community translations**: Download Korean or English translations shared by other users, or share your own.
- **Korean and English UI**: Changing the app language updates the interface, story information, viewer translations, and generated nicknames.
- **Guided tours**: Highlight-based walkthroughs explain initial setup and the viewer controls.

### Installation

1. Download the latest APK from [Releases](../../releases).
2. Allow installation from unknown sources in Android settings when prompted.
3. Launch BBLOG and follow the first-run tutorial to configure the required permissions and settings.

### Notes

- AI translation requires your own API key. Google Gemini, OpenAI, and Claude are supported. You can register a key during the tutorial or later in Settings. Charges may apply depending on usage.
- You can still read official, cached, or community-shared translations without an API key.
- Automatic dialogue detection for the overlay requires Android 14 QPR2 or later. On earlier Android versions, the overlay still works with manual Previous and Next controls.
- This repository is dedicated to distributing installation packages.
