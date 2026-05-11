# 🛍️ Premium Shopping Mall

프리미엄 패션 쇼핑몰 UI/UX를 기반으로 제작한 React 쇼핑몰 프로젝트입니다.  
사용자 중심의 상품 탐색 경험과 직관적인 장바구니 기능 구현에 중점을 두었습니다.

<br/>

---

# 📌 프로젝트 개요

### 📅 개발 기간
2026.05 ~ 2026.05

### 👨‍💻 프로젝트 유형
개인 프로젝트

### 🎯 프로젝트 목적
- 실제 쇼핑몰 서비스 흐름 구현
- React 상태 관리 학습
- 사용자 친화적인 UI/UX 구현
- 컴포넌트 기반 구조 설계 경험

<br/>

---

# ✨ 주요 기능

## 🧥 상품 목록
- 총 12개의 상품 데이터 구성
- 카테고리별 상품 분류
  - 상의
  - 하의
  - 아우터
  - 신발
  - 액세서리

---

## 🔍 상품 검색 기능
- 상품명 기반 실시간 검색
- 입력값에 따라 즉시 필터링

```js id="x7j2f9"
const filteredProducts = products.filter((product) =>
  product.name.toLowerCase().includes(search.toLowerCase())
);
