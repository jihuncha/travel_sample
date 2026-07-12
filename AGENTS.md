# Repository Guidelines

이 repository는 여행 플래너 정적 웹사이트입니다.

## Project Shape

- 중심 파일은 `index.html`입니다.
- 서버, 번들러, 빌드 과정 없이 동작해야 합니다.
- 여행 데이터는 `index.html`의 `days` 배열에서 관리합니다.
- 현재 샘플 데이터는 2026년 10월 파리 + 코펜하겐 일정입니다.

## Editing Rules

- 기존 알고리즘/Kotlin repository 규칙을 이 프로젝트에 적용하지 마세요.
- 사용자가 명시적으로 요청하기 전까지 Kotlin/IntelliJ 샘플 파일은 삭제하지 마세요.
- 모바일에서 보기 쉬운 UI를 우선합니다.
- 지도와 일정이 한 화면에서 함께 확인되는 흐름을 유지합니다.
- Google Directions iframe 대신 My Maps embed와 Google Maps 길찾기 링크 조합을 유지합니다.

## Local Verification

- `index.html`을 브라우저에서 직접 열어 확인합니다.
- 필요하면 `python3 -m http.server 8080`으로 로컬 서버를 띄워 확인합니다.
