# 08. 디자인 시스템 (Design System)

> **프로젝트명**: 플로뜰리에 (Flottelier)  
> **기준 지침**: `CLI-REFERENCE-USAGE.md` 08-design-system 규격 준수  

---

## 1. 디자인 토큰 (Design Tokens)

### 1.1 Color Tokens
```css
:root {
  --color-bg-main: #FAFAFA;
  --color-bg-surface: #F7F5F0;
  --color-brand-primary: #A8C5C6;
  --color-brand-sage: #B3C5B5;
  --color-brand-lavender: #D8D4E2;
  --color-text-primary: #2C2C2C;
  --color-text-secondary: #666666;
  --color-text-muted: #999999;
  --color-border: #E5E2DC;
}
```

### 1.2 Typography Tokens
```css
:root {
  --font-family-serif: 'Noto Serif KR', 'Cormorant Garamond', serif;
  --font-family-sans: 'Pretendard', 'Noto Sans KR', sans-serif;
  --font-size-hero: 42px;
  --font-size-h1: 32px;
  --font-size-h2: 24px;
  --font-size-body: 16px;
  --font-size-small: 14px;
}
```

---

## 2. 컴포넌트 라이브러리 (UI Components)
1. **Button (CTA)**: Primary N Pay 1초 결제 버튼, Secondary 1장 체험팩 환급 버튼, Tertiary 팝업 예약 모달 버튼
2. **Badge**: 4차 정련 Completed 보증 뱃지, 4無 안전성 뱃지, 100% 국산 뱃지
3. **Card**: 80% 여백 비대칭 에디토리얼 카드, 겹수별 용도 비교 카드
4. **Form Controls**: Canvas 자수 폰트/실색상 Picker, 팝업 타임슬롯 픽커 버튼

---

## 3. 600선 확장 컴포넌트 시스템 (신규 추가)
5. **Toast (알림)**: [Sonner](https://sonner.emilkowal.ski) 기반 스택형 토스트 알림 컴포넌트
6. **Drawer (바텀시트)**: [Vaul](https://vaul.emilkowal.ski) 기반 제스처 반응형 모바일 시트 컴포넌트
7. **Bento Card**: [Bento Grids](https://bentogrids.com) 기반 4대 USP 모듈형 그리드 카드
8. **Magnetic Button**: [Dennis Snellenberg](https://dennissnellenberg.com) 벤치마크 자석 호버 버튼
