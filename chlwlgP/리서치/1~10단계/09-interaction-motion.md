# 09. 인터랙션 & 모션 명세 (Interaction & Motion Specs)

> **프로젝트명**: 플로뜰리에 (Flottelier)  
> **기준 지침**: `CLI-REFERENCE-USAGE.md` 09-interaction-motion 규격 준수  

---

## 1. 4차 정련 물결 캔버스 모션 (Water Ripple Canvas)
* **참고 레퍼런스**: `Izanami` (https://izanami-official.com/)
* **구현 방식**: HTML5 WebGL / 2D Canvas 셰이더 기반 마우스 이동 커서 마그네틱 파동
* **적용 위치**: P-01 히어로 비주얼 및 P-02 브랜드 스토리 탑 캔버스
* **제한 사항**: 마우스 호버 시 텍스트 왜곡률 5% 이내 제한, 모바일 터치 시 성능 저하 방지 처리

---

## 2. 유체 스크롤 트랜지션 (Fluid Scroll Transition)
* **참고 레퍼런스**: `NUSET` (https://nuset.jp/)
* **구현 방식**: Locomotive Scroll 연동 패럴랙스 유체 모션
* **적용 위치**: P-01 히어로에서 P-02 브랜드 스토리 섹션 전환 구간 1회성 적용

---

## 3. 실시간 Canvas 자수 합성 엔진 (Canvas Embroidery Engine)
* **참고 레퍼런스**: `Nike By You` + `Fabric.js`
* **구현 방식**: 2D Canvas 이미지 위에 폰트 베지어 곡선 및 실사 실 질감 텍스처 오버레이
* **반응 속도**: 텍스트 입력 후 100ms 이내 실시간 렌더링

---

## 4. 600선 확장 인터랙션 엔진 명세 (신규 추가)
* **스무스 스크롤 표준화**: [Lenis Scroll](https://lenis.darkroom.engineering/)을 적용하여 전 화면에서 프레임 저하 없는 부드러운 스크롤감 제공.
* **마그네틱 버튼 호버**: [Dennis Snellenberg](https://dennissnellenberg.com/) 스타일의 마우스 근접 자석 인력 인터랙션 (Spring physics: stiffness 300, damping 20).
* **고해상도 500% 확대경 렌즈**: [Bottega Veneta](https://www.bottegaveneta.com/) 스타일의 직조 결 돋보기 뷰어.
