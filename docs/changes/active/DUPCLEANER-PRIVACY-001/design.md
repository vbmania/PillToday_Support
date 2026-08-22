# DUPCLEANER-PRIVACY-001 — Design

## 방식

- 온디바이스 파일 처리와 제3자 SDK 전송을 분리해 설명한다.
- Firebase, Google Mobile Ads/UMP, Apple StoreKit별 데이터 범주·목적·사용자 선택을 명시한다.
- ATT를 요청하지 않는 현재 동작을 밝히되 Google의 앱·개발자 범위 식별자 처리 가능성을 숨기지 않는다.
- 한국어·영어 문서가 같은 범위와 의미를 갖게 한다.

## 경계와 롤백

법률 자문을 대신하지 않는다. 실제 SDK나 수집 설정이 바뀌면 정책과 App Store Privacy를 함께 재검토한다. 잘못된 내용이 확인되면 직전 정책으로 되돌리기보다 실제 동작과 일치하도록 즉시 정정한다.
