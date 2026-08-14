# 04. 레퍼런스 분석 (Reference Analysis)

> **프로젝트명**: 플로뜰리에 (Flottelier)  
> **기준 지침**: `CLI-REFERENCE-USAGE.md` 04-reference-analysis 규격 준수 (What works / Apply / Do not copy / UX Rule)  

---

## 1. 레퍼런스별 정밀 분석 (Analysis by Category)

### 1.1 Color & Mood: mira + JIII ATELIER
* **What works (마음에 드는 점)**: 흰색/아이보리 배경 위 저채도 파스텔 컬러 수채화 번짐 레이어링.
* **Apply to Flottelier (플로뜰리에 적용)**: 히어로 비주얼([P-01](file:///C:/chlwlgP/클라이언트/가상%20클라이언트%20설계%20결과/화면_설계서.md#L34)) 및 브랜드 스토리([P-02](file:///C:/chlwlgP/클라이언트/가상%20클라이언트%20설계%20결과/화면_설계서.md#L18))의 부드러운 아쿠아/민트/라벤더 배경 처리.
* **Do not copy (그대로 따라 하지 않을 점)**: 지나치게 몽환적이어서 텍스트 가독성을 떨어뜨리는 시각 효과는 피함.
* **UX Rule**: 본품 구매 및 옵션 선택 영역에서는 수채화 이펙트를 배제하고 맑은 고대비 텍스트 유지.

### 1.2 Image Frame: SHIROITO + DECENCIA
* **What works (마음에 드는 점)**: 사각형 카드의 단순 나열을 벗어난 비대칭 에디토리얼 잡지 프레임, 80% 이상의 여백.
* **Apply to Flottelier (플로뜰리에 적용)**: RITUAL 가이드([P-04](file:///C:/chlwlgP/클라이언트/가상%20클라이언트%20설계%20결과/화면_설계서.md#L19)) 4단계 타임라인 및 소창 소재 화보 연출.
* **Do not copy (그대로 따라 하지 않을 것)**: 카탈로그 라인업([P-05](file:///C:/chlwlgP/클라이언트/가상%20클라이언트%20설계%20결과/화면_설계서.md#L21)) 전체를 비대칭으로 배치하여 제품을 찾기 힘들어지는 구조 방지.

### 1.3 Interaction & Motion: Izanami + NUSET
* **What works (마음에 드는 점)**: 커서 이동 시 부드러운 Canvas 물결(Water Ripple) 반응, 스크롤 연동 유체 트랜지션.
* **Apply to Flottelier (플로뜰리에 적용)**: 메인 히어로([P-01](file:///C:/chlwlgP/클라이언트/가상%20클라이언트%20설계%20결과/화면_설계서.md#L34)) 4차 정련 물결 캔버스 모션 및 첫 진입 스크롤 1회성 리플.
* **Do not copy (그대로 따라 하지 않을 것)**: 결제, 장바구니, 팝업 예약 모달에 물 효과 적용 금지.

### 1.4 E-Commerce UX: Diptyque + Tamburins
* **What works (마음에 드는 점)**: 브랜드 스토리 흐름에서 자연스러운 쇼핑 전환, 세트별 단가 자동 계산기 및 N Pay 1초 결제.
* **Apply to Flottelier (플로뜰리에 적용)**: 상품 상세([P-07](file:///C:/chlwlgP/클라이언트/가상%20클라이언트%20설계%20결과/화면_설계서.md#L52)) 우측 고정 스티키 결제 CTA 및 낱장/세트 장당 단가 계산기.

### 1.5 Customization Studio: Nike By You + Casetify
* **What works (마음에 드는 점)**: 실시간 2D Canvas 자수 문구/폰트/색상 실물 합성 프리뷰.
* **Apply to Flottelier (플로뜰리에 적용)**: GIFT 커스텀([P-09](file:///C:/chlwlgP/클라이언트/가상%20클라이언트%20설계%20결과/화면_설계서.md#L25)) 및 상품 상세 자수 입력 폼.

### 1.6 Pop-up Store Booking: Gentle Monster + Kakao Map
* **What works (마음에 드는 점)**: 타임슬롯 선택 픽커 모달, 잔여 수량 노출, 오프라인 지도 API 연동.
* **Apply to Flottelier (플로뜰리에 적용)**: 성수 팝업 사전예약([P-08](file:///C:/chlwlgP/클라이언트/가상%20클라이언트%20설계%20결과/화면_설계서.md#L24)) 타임슬롯 선택 픽커 모달.

### 1.7 Eco & Trust Cert: Patagonia + Dr. Bronner's + Dermatest
* **What works (마음에 드는 점)**: Eco Specs Sheet, 더마테스트 4無 성적서 원본 PDF, 맘리뷰 필터.
* **Apply to Flottelier (플로뜰리에 적용)**: 4無 안전성 인증([P-03](file:///C:/chlwlgP/클라이언트/가상%20클라이언트%20설계%20결과/화면_설계서.md#L19)) 및 COMMUNITY([P-10](file:///C:/chlwlgP/클라이언트/가상%20클라이언트%20설계%20결과/화면_설계서.md#L26)) 필터링.

---

## 2. 화면별 레퍼런스 적용 요약표

| 화면 ID | 화면명 | 적용 레퍼런스 | 핵심 융합 포인트 |
|---|---|---|---|
| **P-01** | 메인 화면 | mira + Izanami + Diptyque | 파스텔 수채화 배경, 물결 커서 캔버스, 브랜드-쇼핑 결합 |
| **P-02** | BRAND ABOUT | SHIROITO + Patagonia | 여백 80% 비대칭 프레임, 4차 정련 공정표 및 Eco Specs |
| **P-03** | 4無 안전성 인증 | Dr. Bronner's + Dermatest | KC 및 더마테스트 엑설런트 원본 PDF 모달 |
| **P-04** | RITUAL 가이드 | DECENCIA + Brooklinen | 4단계 타임라인, 세탁/건조 가이드 및 PDF 지침 |
| **P-05** | SHOP 라인업 | Nonfiction + OCTAEVO | 겹수/용도별 3중 필터, 1장 체험팩 뱃지 |
| **P-06** | 1장 체험팩 | Casper | 1장 소량 체험 신청 및 본품 구매 시 100% 환급 쿠폰 |
| **P-07** | 상품 상세 | Tamburins + Nike By You | 500% HD 줌, 실시간 Canvas 자수 프리뷰, 단가 계산기 |
| **P-08** | 성수 팝업예약 | Gentle Monster + Kakao Map | 타임슬롯 선택 픽커 모달, 성수 카카오 맵 핀 |
| **P-09** | GIFT 커스텀 | Casetify + Buly | 자수 폰트/실 색상 합성, 고급 선물 포장 샷 |
| **P-10** | COMMUNITY | Glossier + Bamboobies | 맘리뷰/피부타입 3중 필터, 안심 환불 정책 |
| **P-11** | MYPAGE | Dollar Shave Club | 1-Click 동일 조건 재구매 버튼 |
