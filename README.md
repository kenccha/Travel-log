# 🌍 World Top Spots

전세계 도시의 인기 장소를 Google Places API로 찾아주는 웹 앱.

## 주요 기능
- 도시/주소/장소명 검색 + 현재 위치 지원
- 관광지·음식점·카페·파인다이닝·최고 레스토랑 탭 분류
- 평점·리뷰수·가격 필터 및 정렬
- 구글 지도 연동 마커

## 시작하기
1. `keys.example.js` → `keys.js` 복사
2. `BROWSER_KEY`에 Google Maps API 키 입력
3. `top-spots.html`을 브라우저에서 열기

## API 키 설정
```js
// keys.js (커밋 금지 — .gitignore에 포함됨)
window.APP_KEYS = {
  BROWSER_KEY: 'YOUR_GOOGLE_MAPS_BROWSER_KEY'
};
```

## 활성화 필요 API (Google Cloud Console)
- Maps JavaScript API
- Places API (New)
- Geocoding API
