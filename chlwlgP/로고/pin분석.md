# 🔍 레퍼런스 분석 파이프라인 (pin분석.md)

## 1. 개요 (Overview)
본 문서는 `pin.md` 파이프라인 수행 결과로 `C:\chlwlgP\로고\output\` 폴더에 저장된 $N$개의 레퍼런스 이미지를 정밀 분석하고, 이미지 생성 AI(Flow 등)에 사용할 수 있는 최적의 영문 프롬프트를 작성하여 `flow.md`에 기록하는 분석 전용 명세서입니다.

---

## 2. 연쇄 실행 조건 (Execution Condition)
* `pin.md` 실행에 따라 `output` 폴더에 $N$개의 이미지 파일(`younglong_reference_1..N.jpg`) 저장이 완료되는 감지 시 즉시 자동 연쇄 실행된다.
* 사용자가 숫자를 지정한 경우 (예: `3개찾기` ➡️ 3개 수집 ➡️ 3개 분석) 지정된 수량만큼 연쇄 분석을 진행한다.

---

## 3. 레퍼런스 분석 프로토콜 (Analysis Protocol)
`output` 폴더의 수집 레퍼런스 검증 시 확인하는 시각적 분석 항목:

1. **엠블럼 및 네거티브 스페이스 구조**: 꽃/포옹 실루엣, 대칭 유기적 문양, 네거티브 스페이스 완성도
2. **플루이드 레터링 및 획 연관성**: 굵고 부드러운 유기적 멜팅 곡선 및 물방울 결합 획 (Liquid Droplet Strokes)
3. **타이포그래피 완성도**: `Flottelier` 글자/심볼의 가독성과 아르누보/사이케델릭 형태 조화
4. **색상 및 배경 명세**: 단색 순수 검정 (`#000000`) 및 단색 순수 흰색 배경 (`#FFFFFF`)
5. **브랜드 부합성**: `input` 폴더 초안 및 `로고레퍼런스` 스타일의 다정하고 유연한 플루이드 디자인 감성 표현 유무

---

## 4. Flow 프롬프트 작성 5대 규칙

1. **flow 이미지 생성 기능 활용 프롬프트 작성**: Flow 이미지 생성 도구에서 정밀한 로고를 도출할 수 있는 프롬프트를 작성한다.
2. **output레퍼런스를 분석하여 flow에 활용할 수 있는 프롬프트로 작성한다**: 수집된 레퍼런스의 시각적 특징을 프롬프트에 상세 반영한다.
3. **영문 프롬프트로 작성한다**: 100% 영문(English)으로만 작성한다.
4. **실행한 이미지는 "재실행"명령이 입력되기 전까지 다시 작성하지 않는다**: 이미 프롬프트가 작성된 기존 이미지는 "재실행" 명령 전까지 변경하거나 재작성하지 않는다.
5. **작성한 프롬프트는 output폴더안에 flow.md파일에 파일 이름을 대제목으로 작성하고 아래쪽에 프롬프트를 작성한다**:
   - 기록 위치: `C:\chlwlgP\로고\output\flow.md`
   - 양식: 문서 상단 `# <파일명>` 대제목 기술 후 하단에 영문 프롬프트 작성.

---

## 5. 결과 기록 양식 예시 (`output/flow.md`)

```markdown
# younglong_reference_1.jpg

## Flow Image Generation Prompt (영문 프롬프트)

An organic fluid emblem logo for an art studio named 'Flottelier'. Featuring a circular botanical rose bloom silhouette forming an abstract embrace of figures in negative space, with smooth liquid curves and rounded droplet strokes. Pure bold black liquid lettering (#000000) on a flat solid pure white background (#FFFFFF). Minimalist 2D vector emblem, Art Nouveau fluid style, zero shadows, no color, no 3D mockup, high contrast, elegant craft studio logo icon.
```
