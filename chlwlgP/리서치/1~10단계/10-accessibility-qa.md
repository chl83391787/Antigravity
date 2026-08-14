# 10. 접근성 및 QA 검토 (Accessibility & QA Guidelines)

> **프로젝트명**: 플로뜰리에 (Flottelier)  
> **기준 지침**: `CLI-REFERENCE-USAGE.md` 10-accessibility-qa 규격 준수  

---

## 1. 웹 접근성 (WAI-ARIA Guidelines)
* **대체 텍스트 (Alt Text)**: 500% HD Magnifier, 수축 비교 Slider, KC 인증서 PDF, 성수동 오프라인 지도 핀에 descriptive `alt` 속성 부여.
* **키보드 내비게이션 (Focus Trap)**: GNB, 팝업 사전예약 모달, 자수 입력 폼 Tab 키 순서 보장.
* **ARIA Live Region**: 실시간 자수 문구 렌더링 및 단가 자동 계산 시 `aria-live="polite"` 설정.

---

## 2. 반응형 breakpoint & 레이아웃 검증
* **PC (1200px 이상)**: 2컬럼 레이아웃 (좌측 비주얼 / 우측 옵션 폼 고정 스티키)
* **태블릿 (768px ~ 1199px)**: 1.5컬럼 리플로우 그리드
* **모바일 (767px 이하)**: 1컬럼 수직 스택, 하단 고정 스티키 CTA 바 (N Pay 1초 결제)

---

## 3. 유효성 검사 표준 체크리스트 (QA Checklist)
1. **자수 문구 입력창**: 1~15자 제한 (15자 초과 시 `"자수 문구는 1~15자 이내로 입력해 주세요."` 출력)
2. **팝업 날짜/시간**: 타임슬롯 미선택 시 `"방문 희망 시간대를 선택해 주세요."` 출력
3. **체험팩 결제**: 회원 1회 한정 (재신청 시 `"이미 체험팩 혜택을 이용하셨습니다."` 안내)
4. **통합 검색창**: 2자 이상 입력 검증
