# CLI Reference Files Usage

Flottelier CLI에서 레퍼런스 관련 파일을 사용할 때의 기준.

## Files

### 03-reference-classification.md

역할:
- 레퍼런스 목록 확인
- 특정 디자인 요소에 사용할 사이트 찾기
- 새로운 레퍼런스 추가 및 분류
- 레퍼런스 선별 작업

터미널에서 이런 작업을 할 때 읽힌다:

- "현재 Color & Mood 레퍼런스를 확인해."
- "이 사이트를 기존 레퍼런스 중 어느 카테고리에 넣을지 판단해."
- "Interaction 레퍼런스만 기준으로 새로운 후보를 비교해."
- "프레임 구조 레퍼런스를 알려줘."

이 파일만으로 실제 UI를 디자인하도록 지시하지 않는 것을 권장한다.

---

### 04-reference-analysis.md

역할:
- 실제 디자인 설계
- 레퍼런스를 Flottelier에 적용하는 방식 결정
- 가져올 요소와 제외할 요소 확인
- UI / Interaction 구현 방향 결정

터미널에서 이런 작업을 할 때 읽힌다:

- "Home Hero를 설계해."
- "브랜드 스토리 섹션의 이미지 레이아웃을 설계해."
- "물 같은 interaction을 구현해."
- "Flottelier의 visual direction에 맞게 UI를 수정해."

실제 화면을 만들거나 코드를 생성할 때는 classification보다 analysis가 중요하다.

---

# Recommended CLI Flow

## 1. 새로운 레퍼런스를 정리할 때

읽기:
- 03-reference-classification.md

작업:
1. 사이트 확인
2. Color / Frame / Interaction / UX 등으로 분류
3. 선호 여부 기록
4. 분석 가치가 있는 레퍼런스만 선별

---

## 2. 선별된 사이트를 깊게 분석할 때

읽기:
- 03-reference-classification.md
- 04-reference-analysis.md

작업:
1. 기존 기준 확인
2. 새로운 사이트 분석
3. What works
4. Apply to Flottelier
5. Do not copy
6. UX Rule

---

## 3. 실제 페이지를 디자인할 때

우선 읽기:
- Brand Research
- Persona / UX Requirements
- 04-reference-analysis.md
- Design & UX Direction
- 해당 Page Spec

필요한 경우 추가:
- 03-reference-classification.md

중요:
실제 화면 설계 시 classification 파일만 넣지 않는다.
classification은 '어떤 사이트를 어떤 목적으로 보는지'를 알려주는 색인에 가깝다.
analysis는 '그 요소를 Flottelier에서 어떻게 사용할지'를 알려준다.

---

# Simple Rule

새 사이트를 정리한다
→ classification

왜 좋은지 판단한다
→ classification + analysis

실제 화면을 만든다
→ brand research + analysis + design direction + page spec

레퍼런스를 다시 찾는다
→ classification

모션을 구현한다
→ analysis + interaction spec

쇼핑 UX를 설계한다
→ persona/UX requirements + analysis + IA/page spec

---

# Recommended Folder Example

docs/
├── 01-brand-research.md
├── 02-personas.md
├── 03-reference-classification.md
├── 04-reference-analysis.md
├── 05-design-ux-direction.md
├── 06-information-architecture.md
├── 07-page-specs.md
├── 08-design-system.md
├── 09-interaction-motion.md
└── 10-accessibility-qa.md
