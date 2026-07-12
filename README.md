# Travel Sample

휴대폰에서 URL로 바로 열어볼 수 있는 정적 여행 플래너 샘플입니다.

현재 샘플 데이터는 2026년 10월 파리 + 코펜하겐 일정입니다. 프로젝트 문구는 특정 여행 유형에 묶이지 않도록 `여행 플래너` 기준으로 관리합니다.

## Features

- 일별 일정 목록
- 도시 필터와 일정 검색
- 날짜별 시간표
- 날짜별 체크리스트
- 브라우저 자동 저장 메모
- Google Maps 길찾기 링크
- Google My Maps embed
- 로컬 SVG 간이지도

## Local Preview

빌드나 서버 없이 브라우저에서 `index.html`을 열면 됩니다.

```sh
open index.html
```

로컬 서버로 확인하고 싶다면 다음 명령을 사용할 수 있습니다.

```sh
python3 -m http.server 8080
```

그 다음 브라우저에서 `http://localhost:8080`을 엽니다.

## Edit Travel Data

여행 데이터는 `index.html` 안의 `days` 배열에서 수정합니다.

각 날짜 항목에는 날짜, 제목, 도시, 상태, 지도 레이어, 동선, 메모, Google 길찾기 URL, 시간표, 체크리스트, 지도 포인트가 들어 있습니다.

## Deploy With GitHub Pages

1. GitHub repository의 `Settings`로 이동합니다.
2. `Pages` 메뉴를 엽니다.
3. `Source`를 `Deploy from a branch`로 설정합니다.
4. Branch는 `main`, folder는 `/root`로 설정합니다.
5. 예상 URL은 `https://jihuncha.github.io/travel_sample/`입니다.

## Notes

Google My Maps가 보이지 않으면 My Maps 공유 설정을 `링크가 있는 사용자 보기 가능`으로 바꿔야 합니다.
