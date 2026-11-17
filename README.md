# 진삼국지 — Privacy Policy / 개인정보처리방침

App: 진삼국지 / Jin Samgukji (`com.mudangstudio.jinsam`)
Last updated / 최종 수정일: 17 November 2026

Web page: <https://ted19.github.io/jinsam-privacy/>

`version.json` in this repository tells the app the minimum version that can still be played (forced update). / 이 저장소의 `version.json`은 앱이 계속 플레이할 수 있는 최소 버전을 알려 줍니다(강제 업데이트).

---

# English

## Summary

진삼국지 (Jin Samgukji) is a single-player strategy game set in the Three Kingdoms era. The game runs entirely on your device. Your saved games and settings stay on your device.

The current version shows no ads. The app includes the Google Mobile Ads (AdMob) SDK so that ads can be shown in a future update; see "Advertising" below. The app has no account system, no analytics and no crash reporting of its own. We do not collect personal data and we operate no servers.


## The app in one line

You rule a Three Kingdoms faction on a strategy map (domestic affairs, diplomacy, officers) and fight hex-grid battles. All game logic runs on your device and works offline.


## What we collect

We do not collect personal data. We receive no saved games, settings, play records or device identifiers from the app.

Google, our advertising provider, may collect the information described under "Advertising". When ads are shown, we can see only aggregated ad reports in AdMob (for example, the number of ad impressions), which do not identify you.


## Advertising (Google AdMob)

- **Current version:** ads are turned off. The app does not request or show ads.
- **When ads are turned on in a future update:** a banner at the bottom of the title screen. There are no ads on the strategy map or battle screens.
- **Who collects the data:** Google, through the Google Mobile Ads SDK, under its own privacy policy:
- **What the SDK may collect:**
  - Device identifiers: the advertising ID (Android advertising ID), the app set ID, and identifiers from Android's Privacy Sandbox ad APIs (Topics, attribution) where available.
- Device and app information: device model, operating system version, language, screen size, app name and version, and network type.
- Approximate location derived from your IP address. The app does not request location permission.
- App interactions with ads: ad impressions and taps.
- Diagnostics: ad SDK performance and error information.
- **Why:** to show ads, to measure ad performance, to prevent fraud and abuse, and, if you allow it, to personalise ads.
- **What the SDK never receives:** your saved games or settings. The app does not pass them to the ad SDK.
- **Sharing:** the information above is collected by Google and may be shared with Google's advertising partners as described in Google's policies:

## Your choices for ads

- **Advertising ID:** you can reset or delete your advertising ID, or opt out of personalised ads, in Android Settings > Privacy > Ads (the exact path depends on your device).
- **Learn more:**

## Data stored on your device

- **Saved games:** the automatic save and up to three manual save slots, kept in the app's own private storage.
- **Settings:** battle cut-in mode, hero introduction on/off, and sound effect volume.
- Other apps cannot read this data. You can delete all saved games at any time in the title screen under Settings > Saved data > Delete all. Everything is removed when you uninstall the app.
- **Android backup:** if Android's automatic backup is turned on for your Google account, Android may include the app's saved data in your device backup. This backup is handled by Google under your account settings; we cannot access it. You can turn it off in Android Settings > Google > Backup (the exact path depends on your device).

## Update check

- When the app starts (and when you return to it), it downloads a small file, `https://ted19.github.io/jinsam-privacy/version.json`, which says the minimum app version that can still be played. If your version is older, the app asks you to update from the Google Play Store.
- The request contains no game data and no identifiers from the app. As with any web request, the hosting provider, GitHub, receives your IP address and basic technical information (such as the browser engine and device type in the user agent) and may keep it in its logs. GitHub's privacy statement:
- If you are offline, the check is skipped and you can keep playing.

## Links you open

- If you open this policy or the store page from the app, it opens in your web browser or the Google Play Store app, which are separate software with their own privacy policies.

## Network access

- The app's own code uses the network only for the update check above. Fonts, images and sounds are bundled in the app; gameplay does not use the network.
- The Google ad SDK uses the network to load ads (only when ads are turned on).
- Saved games and settings are never sent over the network.

## Permissions the app declares

| Permission | Why |
|---|---|
| `INTERNET` | The update check (reading `version.json`), and the Google ad SDK to load ads. |
| `ACCESS_NETWORK_STATE` | Used by the Google ad SDK to check for a connection before requesting ads. |
| `com.google.android.gms.permission.AD_ID` | Used by the Google ad SDK to read the advertising ID. |
| `ACCESS_ADSERVICES_AD_ID`, `ACCESS_ADSERVICES_ATTRIBUTION`, `ACCESS_ADSERVICES_TOPICS` | Used by the Google ad SDK for Android's Privacy Sandbox ad APIs, where available. |
| `WAKE_LOCK`, `FOREGROUND_SERVICE` | Added by a background-task library (WorkManager) that the Google ad SDK uses. The app itself runs no foreground service. |
| `DYNAMIC_RECEIVER_NOT_EXPORTED_PERMISSION` | Added automatically by Android libraries to protect the app's own internal messages. It gives no access to your data. |
The app keeps the screen on while it is open so the game does not sleep during play; this needs no permission and involves no data.


## Children

The app is intended for a general audience and is not directed at children under 13 (or the minimum age in your country). We do not knowingly collect personal data from children.


## Changes to this policy

If this policy changes, the updated text will be published at this address and the date above will be revised.


## Contact

For questions about this policy, please use the developer contact details shown on the Google Play listing for 진삼국지.


---

# 한국어

## 요약

진삼국지는 삼국 시대를 배경으로 한 1인용 전략 게임입니다. 게임은 모두 기기 안에서 돌아가며, 저장한 게임과 설정은 기기 밖으로 나가지 않습니다.

현재 버전은 광고를 표시하지 않습니다. 앞으로의 업데이트에서 광고를 표시할 수 있도록 앱에 Google 모바일 광고(AdMob) SDK가 들어 있습니다(아래 "광고" 참고). 앱 자체에는 계정 기능, 분석 도구, 크래시 리포팅이 없습니다. 저희(개발자)는 개인정보를 수집하지 않으며 서버를 운영하지 않습니다.


## 앱 소개

천하 지도에서 삼국의 한 세력을 이끌어(내정·외교·인사) 육각 전장에서 싸우는 전략 게임입니다. 모든 게임 처리는 기기 안에서 이루어지며 인터넷 없이도 할 수 있습니다.


## 수집하는 정보

저희는 개인정보를 수집하지 않습니다. 앱으로부터 저장 게임, 설정, 플레이 기록, 기기 식별자를 받지 않습니다.

광고 제공자인 Google은 아래 "광고"에 적힌 정보를 수집할 수 있습니다. 광고를 표시하는 경우 저희는 AdMob에서 사용자를 식별할 수 없는 집계 보고서(예: 광고 노출 수)만 볼 수 있습니다.


## 광고 (Google AdMob)

- **현재 버전:** 광고가 꺼져 있습니다. 앱은 광고를 요청하거나 표시하지 않습니다.
- **앞으로 광고를 켜는 경우:** 처음 화면 아래쪽의 배너입니다. 천하 지도와 전투 화면에는 광고가 없습니다.
- **수집 주체:** Google이 Google 모바일 광고 SDK를 통해 수집하며, Google의 개인정보처리방침을 따릅니다:
- **SDK가 수집할 수 있는 정보:**
  - 기기 식별자: 광고 ID(Android 광고 ID), 앱 세트 ID, 그리고 지원되는 기기에서 Android 개인정보 보호 샌드박스 광고 API(Topics, 기여 분석)의 식별자
- 기기·앱 정보: 기기 모델, 운영체제 버전, 언어, 화면 크기, 앱 이름과 버전, 네트워크 종류
- IP 주소로 추정한 대략적인 위치. 앱은 위치 권한을 요청하지 않습니다.
- 광고와의 상호작용: 광고 노출, 탭
- 진단 정보: 광고 SDK의 성능과 오류 정보
- **목적:** 광고 표시, 광고 성과 측정, 사기·악용 방지, 그리고 사용자가 허용한 경우 맞춤 광고
- **광고 SDK에 전달하지 않는 정보:** 저장 게임과 설정. 앱은 이 정보를 광고 SDK에 넘기지 않습니다.
- **제공:** 위 정보는 Google이 수집하며, Google 정책에 따라 Google의 광고 파트너와 공유될 수 있습니다:

## 광고 관련 선택권

- **광고 ID:** Android 설정 > 개인정보 보호 > 광고(기기에 따라 경로가 다를 수 있음)에서 광고 ID를 재설정·삭제하거나 맞춤 광고를 거부할 수 있습니다.
- **자세히 보기:**

## 기기에 저장되는 정보

- **저장 게임:** 자동 저장과 수동 저장 슬롯(최대 3개)을 앱 전용 저장 공간에 보관합니다.
- **설정:** 전투 연출 방식, 무장 등장 연출 켬/끔, 효과음 크기
- 다른 앱은 이 정보를 읽을 수 없습니다. 처음 화면의 설정 > 저장 데이터 > 모두 지우기에서 언제든 저장 게임을 지울 수 있으며, 앱을 삭제하면 모두 사라집니다.
- **Android 백업:** 사용자의 Google 계정에서 Android 자동 백업이 켜져 있으면, Android가 앱의 저장 데이터를 기기 백업에 포함할 수 있습니다. 이 백업은 사용자의 계정 설정에 따라 Google이 처리하며 저희는 접근할 수 없습니다. Android 설정 > Google > 백업(기기에 따라 경로가 다를 수 있음)에서 끌 수 있습니다.

## 업데이트 확인

- 앱을 시작할 때(그리고 앱으로 돌아올 때) 작은 파일 `https://ted19.github.io/jinsam-privacy/version.json`을 내려받습니다. 이 파일에는 계속 플레이할 수 있는 최소 앱 버전이 적혀 있으며, 사용 중인 버전이 그보다 낮으면 Google Play 스토어에서 업데이트하도록 안내합니다.
- 이 요청에는 게임 데이터나 앱의 식별자가 담기지 않습니다. 다만 여느 웹 요청과 마찬가지로, 파일을 호스팅하는 GitHub가 IP 주소와 기본 기술 정보(사용자 에이전트의 브라우저 엔진·기기 종류 등)를 받아 기록할 수 있습니다. GitHub 개인정보처리방침:
- 인터넷에 연결되어 있지 않으면 확인을 건너뛰고 계속 플레이할 수 있습니다.

## 앱에서 여는 링크

- 앱에서 이 방침이나 스토어 페이지를 열면 웹 브라우저나 Google Play 스토어 앱에서 열립니다. 이들은 자체 개인정보처리방침을 따르는 별도 소프트웨어입니다.

## 네트워크 접근

- 앱 자체 코드는 위의 업데이트 확인에만 네트워크를 씁니다. 글꼴·그림·소리는 앱에 들어 있으며, 게임 플레이에는 네트워크를 쓰지 않습니다.
- Google 광고 SDK는 광고를 불러올 때 네트워크를 씁니다(광고를 켰을 때만).
- 저장 게임과 설정은 네트워크로 보내지 않습니다.

## 앱이 선언하는 권한

| 권한 | 이유 |
|---|---|
| `INTERNET` | 업데이트 확인(`version.json` 읽기), 그리고 Google 광고 SDK가 광고를 불러올 때. |
| `ACCESS_NETWORK_STATE` | Google 광고 SDK가 광고를 요청하기 전에 연결 상태를 확인할 때 사용. |
| `com.google.android.gms.permission.AD_ID` | Google 광고 SDK가 광고 ID를 읽을 때 사용. |
| `ACCESS_ADSERVICES_AD_ID`, `ACCESS_ADSERVICES_ATTRIBUTION`, `ACCESS_ADSERVICES_TOPICS` | 지원되는 기기에서 Google 광고 SDK가 Android 개인정보 보호 샌드박스 광고 API를 쓸 때 사용. |
| `WAKE_LOCK`, `FOREGROUND_SERVICE` | Google 광고 SDK가 쓰는 백그라운드 작업 라이브러리(WorkManager)가 추가합니다. 앱 자체는 포그라운드 서비스를 실행하지 않습니다. |
| `DYNAMIC_RECEIVER_NOT_EXPORTED_PERMISSION` | 앱 내부 메시지를 보호하기 위해 Android 라이브러리가 자동으로 추가합니다. 사용자 데이터에 접근하지 않습니다. |
게임하는 동안 화면이 꺼지지 않도록 앱이 열려 있는 동안 화면을 켜 둡니다. 이 기능에는 권한이 필요 없으며 어떤 정보도 다루지 않습니다.


## 아동

이 앱은 일반 이용자를 대상으로 하며 만 14세 미만(또는 거주 국가의 기준 연령 미만) 아동을 대상으로 하지 않습니다. 저희는 아동의 개인정보를 알면서 수집하지 않습니다.


## 방침 변경

방침이 변경되면 이 주소에 갱신된 내용을 게시하고 위 날짜를 수정합니다.


## 문의

방침 관련 문의는 진삼국지의 Google Play 스토어 등록정보에 표시된 개발자 연락처를 이용해 주십시오.

