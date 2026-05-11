# 🛒 Premium Shopping Mall
Premium shopping

세련된 UI와 사용자 중심 UX를 갖춘 프리미엄 쇼핑몰 웹 애플리케이션입니다.  
상품 탐색부터 장바구니 관리까지 실제 이커머스 환경을 고려하여 제작되었습니다.

---

## ✨ 주요 기능

### 🧥 상품 목록
- 총 12개의 프리미엄 상품 제공
- 카테고리 구성
  - 상의
  - 하의
  - 아우터
  - 신발
  - 액세서리

---

### 🔍 상품 검색
- 상품명 기반 실시간 검색 기능
- 입력과 동시에 필터링

```js
const filteredProducts = products.filter((product) =>
  product.name.toLowerCase().includes(search.toLowerCase())
);
