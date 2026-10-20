# autoBlog (TripWriter)

여행지 이름만 입력하면 AI(Gemini)가 블로그용 여행 후기 글을 자동으로 써주는 도구.

## 구성
- `index.html` — 메인 페이지 (TripWriter — 여행 블로그 자동생성)
- `index_V260806.html` — 이전 버전 스냅샷

## 주요 기능 (코드 기준)
- 이번 달 인기 해외여행지 TOP10, 실시간 인기 검색어 등 트렌드 참고 섹션
- Gemini API 키를 브라우저에 저장해서 호출 (`aistudio.google.com/apikey`에서 발급)
- 여행지·글 제목을 입력하면 본문/이미지(Pexels API)/해시태그를 생성
- `autoDiary`(TravelBlog AI)와 유사한 컨셉이지만 별도 구현체
