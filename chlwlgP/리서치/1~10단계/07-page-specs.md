# 07. 화면 설계서 (Page Specifications)

> **프로젝트명**: 플로뜰리에 (Flottelier)  
> **기준 지침**: `CLI-REFERENCE-USAGE.md` 07-page-specs 규격 준수  

---

## 1. 전체 화면 목록 (Screen Directory)
1. **P-01**: 메인 화면 (HOME)
2. **P-02**: BRAND ABOUT 화면
3. **P-03**: 4無 안전성 인증 화면 (KC Cert & Dermatest Modal)
4. **P-04**: RITUAL & CARE 가이드 화면 (4-Step Timeline & PDF)
5. **P-05**: SHOP 라인업 전체보기 화면 (Product Catalog & Filter)
6. **P-06**: 1장 체험팩 신청 화면 (Trial Kit & 100% Refund Coupon)
7. **P-07**: 상품 상세 화면 (Product Detail, 500% HD Zoom, Canvas Embroidery, Price Calc)
8. **P-08**: 성수 팝업스토어 사전예약 화면 (Pop-up Store & Kakao Map)
9. **P-09**: GIFT 커스텀 스튜디오 화면 (Custom Embroidery & Gift Packaging)
10. **P-10**: COMMUNITY & REVIEWS 화면 (Mom Reviews & Sensitive Refund)
11. **P-11**: MYPAGE 1-Click 재구매 화면 (Quick Re-order)
12. **P-12**: EXCEPTION 예외 처리 화면 (404 Not Found)

---

## 2. 대표 주요 화면 명세

### 2.1 P-01: 메인 화면 (HOME)
* **목적**: 맑고 고요한 브랜드 첫인상 전달, 4차 정련 완료 보증, 성수 팝업 사전예약 진입 유도
* **구성 요점**:
  * GNB 6대 메뉴 헤더, 물 속 원단 모션 비주얼 플레이스홀더 히어로
  * KC 공인 인증 / 4차 삶기 완료 / 4無 인증 뱃지
  * 성수 팝업 사전예약 모달 버튼, 세탁 PDF 다운로드 푸터

### 2.2 P-07: 상품 상세 화면 (Product Detail & Custom)
* **목적**: 500% HD 줌, 실시간 Canvas 자수 프리뷰, 단가 계산기로 구매 결제 전환 유도
* **인터랙션 명세**:
  * 좌측: 돋보기 호버 시 500% HD Magnifier 생성, 세탁 전/후 1:1 수축 비교 Slider
  * 우측: 실시간 Canvas 자수 입력창(문구/폰트/컬러), 낱장/세트 장당 단가 계산기, N Pay 1초 결제 버튼
  * 유효성 검사: 자수 문구 15자 초과 시 `"자수 문구는 최대 15자까지 입력 가능합니다."` 메세지 출력
