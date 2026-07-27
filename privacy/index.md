---
layout: page
title: 개인정보처리방침 · Privacy Policy
permalink: /privacy/
---

# BBLOG 개인정보처리방침

시행일: 2026년 7월 27일  
개발자: cometes  
문의: [vloslain@gmail.com](mailto:vloslain@gmail.com)

cometes(이하 “개발자”)는 BBLOG 이용자의 개인정보를 중요하게 생각하며 다음과 같이 처리합니다.

## 1. 처리하는 정보와 목적

BBLOG의 번역 보기 등 기본 기능은 계정 없이 사용할 수 있습니다. 번역 공유, 투표, 신고 등 커뮤니티 기능을 이용하기 위해 Google 로그인을 선택하면 Google 계정 이메일 주소와 Firebase 사용자 식별자가 Firebase Authentication을 통해 처리됩니다. 이용자가 정한 닉네임은 커뮤니티 프로필과 공유 게시물의 작성자명으로 공개됩니다.

이용자가 번역 공유를 직접 선택하면 번역문, 스토리 식별 정보, 닉네임, 작성 시각 및 반응 수가 Firebase Cloud Firestore에 저장되고 다른 이용자에게 공개됩니다. 좋아요, 싫어요와 그 사유, 신고 사유 및 신고 내용은 커뮤니티 운영과 부적절한 콘텐츠 검토에 사용됩니다.

관리자 계정에서는 신고 알림을 보내기 위해 Firebase Cloud Messaging 기기 토큰을 처리할 수 있습니다.

## 2. 기기에서만 처리되는 정보

번역 기록, 읽기 진행도 및 앱 설정은 원칙적으로 이용자의 기기에 저장됩니다. Android 시스템 백업 또는 이용자가 직접 생성한 백업 파일에 포함될 수 있습니다.

이용자가 등록한 Gemini, Vertex AI, OpenAI 또는 Anthropic API 인증정보는 Android Keystore 기반 암호화 저장소에 보관되며 BBLOG 개발자 서버로 전송하거나 개발자가 열람하지 않습니다. 인증정보와 번역할 원문은 이용자가 선택한 AI 제공자에게 기기에서 직접 전송되며 해당 제공자의 개인정보처리방침과 데이터 처리 조건이 적용됩니다. API 인증정보는 Android 앱 백업 대상에서 제외됩니다.

자동 동기화를 사용하면 Android MediaProjection 권한으로 FGO 화면을 캡처해 기기에서 대사 위치를 인식합니다. 캡처 이미지는 BBLOG 서버에 업로드하거나 계정에 저장하지 않습니다.

## 3. 외부 서비스

BBLOG는 기능 제공을 위해 다음 서비스를 사용합니다.

- Google Firebase Authentication, Cloud Firestore, Cloud Functions 및 Cloud Messaging: 로그인, 커뮤니티 저장, 계정 삭제 및 관리자 알림
- Atlas Academy API: FGO 공개 게임 데이터와 배너 이미지 조회
- 이용자가 선택한 Google Gemini/Vertex AI, OpenAI 또는 Anthropic API: 번역 생성

각 서비스는 서비스 제공 과정에서 IP 주소, 기기 또는 요청 로그 등 자체 정책상 필요한 정보를 처리할 수 있습니다.

## 4. 보관 및 삭제

커뮤니티 계정 정보는 이용자가 계정을 삭제할 때까지 보관합니다. 앱의 `설정 → 마이페이지 → 계정 삭제`에서 Firebase 로그인 계정 연결, 커뮤니티 프로필, 닉네임 예약, 투표 및 신고 기록을 삭제할 수 있습니다.

이용자가 공유한 번역문은 다른 이용자가 계속 사용할 수 있도록 보존될 수 있습니다. 계정 삭제 시 해당 번역에서 작성자 Firebase 식별자와 닉네임을 제거하고 `탈퇴한 사용자`로 표시하여 삭제된 계정과 다시 연결할 수 없도록 익명화합니다.

계정 삭제는 기기에 저장된 번역, 읽기 기록, 앱 설정 및 사용자가 별도로 저장한 백업 파일을 삭제하지 않습니다. 이러한 정보는 앱 데이터 삭제 또는 백업 파일 삭제를 통해 이용자가 직접 제거할 수 있습니다.

앱을 사용할 수 없는 경우 [계정 및 데이터 삭제 안내]({{ '/account-deletion/' | relative_url }})에 따라 이메일로 삭제를 요청할 수 있습니다. 확인이 완료된 요청은 원칙적으로 30일 이내에 처리합니다. 법률상 보관 의무가 있거나 보안·사기 방지를 위해 필요한 경우에는 해당 목적과 기간에 한해 일부 기록을 보관할 수 있습니다.

## 5. 이용자의 선택과 권리

Google 로그인과 커뮤니티 참여는 선택 사항입니다. 이용자는 언제든지 로그아웃하거나 계정을 삭제할 수 있고, 자신이 공유한 게시물을 숨기거나 삭제할 수 있습니다. 개인정보 관련 문의와 열람·정정·삭제 요청은 [vloslain@gmail.com](mailto:vloslain@gmail.com)으로 보낼 수 있습니다.

## 6. 아동의 개인정보

BBLOG는 아동을 주된 대상으로 하지 않습니다. 적용되는 법률상 보호자 동의 없이 아동의 개인정보를 고의로 수집하지 않습니다.

## 7. 보안

BBLOG는 HTTPS 통신, Firebase 보안 규칙, 인증 기반 접근 통제 및 Android Keystore 기반 암호화 저장을 사용합니다. 다만 어떠한 전송 또는 저장 방식도 절대적인 보안을 보장할 수는 없습니다.

## 8. 변경 및 문의

이 방침이 변경되면 이 페이지에 시행일과 변경 내용을 알립니다.

---

<a id="english"></a>

# BBLOG Privacy Policy

Effective date: July 27, 2026  
Developer: cometes  
Contact: [vloslain@gmail.com](mailto:vloslain@gmail.com)

cometes (“the Developer”) respects the privacy of BBLOG users and handles information as described below.

## 1. Information processed and purposes

Core features, including viewing translations, can be used without an account. If a user chooses Google Sign-In for community features such as sharing translations, voting, or reporting content, the user's Google account email address and Firebase user identifier are processed through Firebase Authentication. A nickname chosen by the user is displayed publicly on the community profile and shared posts.

When a user explicitly shares a translation, the translated text, story identifiers, nickname, creation time, and engagement counts are stored in Firebase Cloud Firestore and displayed to other users. Likes, dislikes and their reasons, report reasons, and report details are used to operate and moderate the community.

Firebase Cloud Messaging device tokens may be processed for administrator accounts to deliver moderation alerts.

## 2. Information processed only on the device

Translation history, reading progress, and app settings are generally stored on the user's device. They may be included in Android system backups or backup files created by the user.

Gemini, Vertex AI, OpenAI, or Anthropic API credentials supplied by the user are stored in Android Keystore-backed encrypted storage. They are not sent to or accessible by a BBLOG developer server. Credentials and source text are sent directly from the device to the AI provider selected by the user, subject to that provider's privacy policy and data-processing terms. API credentials are excluded from Android app backups.

When automatic synchronization is enabled, BBLOG uses Android MediaProjection to capture the FGO screen and identify the current dialogue position on the device. Captured images are not uploaded to BBLOG servers or stored with the user's account.

## 3. Third-party services

BBLOG uses:

- Google Firebase Authentication, Cloud Firestore, Cloud Functions, and Cloud Messaging for sign-in, community storage, account deletion, and administrator notifications
- Atlas Academy API for public FGO game data and banner images
- Google Gemini/Vertex AI, OpenAI, or Anthropic API selected by the user for translation generation

Each provider may process information such as IP addresses, device data, or request logs as necessary under its own policies.

## 4. Retention and deletion

Community account information is retained until the user deletes the account. Users can delete their Firebase sign-in connection, community profile, nickname reservation, votes, and reports in `Settings → My Page → Delete Account`.

Translations shared by the user may be retained so that they remain available to the community. On account deletion, the author's Firebase identifier and nickname are removed from those translations, they are displayed as submitted by a `Deleted user`, and they can no longer be linked back to the deleted account.

Account deletion does not remove translations, reading history, app settings, or separately saved backup files stored on the device. Users can remove these by clearing BBLOG app data and deleting their backup files.

If the app cannot be accessed, follow the [Account and Data Deletion instructions]({{ '/account-deletion/#english' | relative_url }}) to request deletion by email. Verified requests are normally processed within 30 days. Limited records may be retained where required by law or for a necessary security or fraud-prevention purpose.

## 5. User choices and rights

Google Sign-In and community participation are optional. Users may sign out or delete their account at any time and can hide or delete translations they have shared. Requests to access, correct, or delete personal information may be sent to [vloslain@gmail.com](mailto:vloslain@gmail.com).

## 6. Children's privacy

BBLOG is not primarily directed at children and does not knowingly collect children's personal information without any consent required by applicable law.

## 7. Security

BBLOG uses HTTPS, Firebase Security Rules, authenticated access controls, and Android Keystore-backed encrypted storage. No transmission or storage method can guarantee absolute security.

## 8. Changes and contact

If this policy changes, the effective date and relevant changes will be posted on this page.
