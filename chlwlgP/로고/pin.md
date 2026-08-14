# 📌 핀터레스트 레퍼런스 수집 파이프라인 (pin.md)

## 1. 개요 (Overview)
본 문서는 `C:\chlwlgP\로고\input\` 폴더의 이미지 파일과 `C:\chlwlgP\로고\로고레퍼런스\` 폴더의 레퍼런스 스타일을 기반으로 핀터레스트에서 유사한 최적의 2D 흑백 로고 레퍼런스를 탐색 및 수집하기 위한 수집 전용 명세서입니다.

---

## 2. 수집 트리거 및 동작 조건 (Trigger Rules)
* **트리거 명령**: `실행 시작`, `레퍼런스 수집 시작해`, 또는 `실행 시작 <N>` (예: `3개찾기`, `실행 시작 5`)
* **참조 폴더**:
  - `C:\chlwlgP\로고\input\` (`로고 초안.png`, `영롱함.png`)
  - `C:\chlwlgP\로고\로고레퍼런스\` (`image.png` 스타일: 대칭 식물 문양, 아르누보 유기적 엠블럼)
* **수집 동작**:
  1. 지정된 숫자 $N$개(기본값 $N=1$)만큼 핀터레스트에서 유사 로고 이미지를 탐색 및 캡쳐한다.
  2. 탐색된 레퍼런스는 `C:\chlwlgP\로고\output\` 폴더에 `.jpg` 파일 포맷으로 저장한다.
  3. 파일명 규칙: `younglong_reference_<순번>.jpg` (예: `younglong_reference_1.jpg`)

---

## 3. 핀터레스트 탐색 쿼리 스펙 (Search Queries)

### [유형 A] 엠블럼 & 네거티브 스페이스 (Symbol / Emblem)
1. `organic fluid embrace logo black and white` (포옹/유기적 곡선 심볼)
2. `floral negative space logo emblem flat vector` (식물 게슈탈트 네거티브 스페이스)
3. `blob organic typography emblem black outline` (유기적 라인 엠블럼)

### [유형 B] 타이포그래피 & 워드마크 (Typography / Wordmark)
1. `fluid liquid typography logo black and white` (리퀴드 타이포그래피)
2. `organic melting font wordmark logo flat vector` (멜팅 워드마크)
3. `psychedelic liquid lettering logo white background` (사이케델릭/아르누보 레터링)

---

## 4. 수집 검증 및 필터링 제약 조건 (Exclusion Rules)
* **배경 명세**: 90% 이상 단색 순수 흰색 배경 (`#FFFFFF`, Flat White)
* **컬러 제약**: 채도 0% 흑백 단색 (`#000000`, Pure Black Line/Vector Only)
* **금지 요소**:
  - ❌ **No Color**: 컬러, 파스텔, 수채화, 그라데이션 금지
  - ❌ **No Mockup**: 명함, 간판, 종이 질감 목업 금지
  - ❌ **No 3D/Shadow**: 3D 입체, 엠보싱, 그림자(Drop Shadow) 금지

---

## 5. 저장 완료 후 다음 파이프라인 연계
* `output` 폴더에 $N$개 이미지 파일 저장이 완료되는 즉시 자동으로 **`pin분석.md`** 파이프라인을 트리거하여 분석을 연쇄 실행한다.
