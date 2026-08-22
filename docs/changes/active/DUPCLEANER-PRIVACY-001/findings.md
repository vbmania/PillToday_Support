# DUPCLEANER-PRIVACY-001 — Findings

## 사실

- DupCleaner는 Firebase Analytics, Firebase Crashlytics, Google Mobile Ads 13.8.0, UMP 3.1.0 및 StoreKit을 사용한다.
- 기존 정책의 “광고 없음”, “Crashlytics 외 분석 SDK 없음” 문구는 현재 소스와 충돌했다.
- Google의 iOS App Store 데이터 공개 문서는 IP 기반 대략적 위치, 크래시·성능, 기기 식별자, 광고 데이터와 제품 상호작용을 수집 가능 범주로 설명한다.
- 앱은 ATT 권한을 요청하지 않으며 IDFA에 직접 접근하지 않는다.

## 결정

- 파일 내용·해시는 로컬 처리임을 유지한다.
- 제3자 데이터 처리는 가능성을 축소 표현하지 않고 서비스별로 공개한다.
- 개인정보 법률 검토는 권장하지만, 심사 전 현재 소스와 정책·스토어 선언의 사실 정합성을 먼저 맞춘다.

## 근거

- https://developers.google.com/admob/ios/privacy/data-disclosure
- https://developers.google.com/admob/ios/privacy
- https://policies.google.com/technologies/partner-sites
