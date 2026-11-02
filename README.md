# aidreamer.co.kr

에이아이드리머 회사 소개 페이지. GitHub Pages 로 `aidreamer.co.kr` 에 서비스한다.

- `index.html` 한 장짜리 정적 페이지
- `CNAME` — GitHub Pages 커스텀 도메인 설정
- DNS: 닷네임 A 레코드 4개 → GitHub Pages

플로우맵 앱과 약관은 `flowmap.aidreamer.co.kr` 에 따로 있다(base44).

## flowmap/

플로우맵 개인정보처리방침·이용약관·계정 삭제 안내. Play 스토어에 이 주소를 등록한다.

직접 고치지 않는다. 플로우맵 저장소의 `scripts/export-legal.py` 가 앱 화면을 그대로
렌더링해 만든 사본이다. 원본(`src/pages/*.jsx`)을 고친 뒤 스크립트를 다시 돌린다.
