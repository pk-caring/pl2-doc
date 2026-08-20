# pl2-doc — Caring M 문서 사이트

Caring M 워크스페이스(`pk-caring/caring_m`)의 구조를 처음 보는 사람에게 설명하는 정적 사이트.
PL-2 M 플랫폼(팔·주행·리더·모방학습·조립) 위에 케어링 기능 계층(`cr_*`, 북치기)이 얹힌 형태를 그대로 담는다.

- `index.html` — 접이식 폴더 트리 (전체 구조 → 펼치면 설명 + 상세 링크) + 층 지도
- `packages.html` — 패키지 목록
- `pkg-*.html` — 패키지 상세: 정의 · 상호작용 다이어그램 · 핵심 · 예시 · 실전 코드
  - `pkg-caring.html` — 케어링 계층 셋(interfaces · percussion · studio)
  - `pkg-motion-filter.html` — 모든 intent 가 지나는 움직임 필터
- `vendor/` — mermaid · highlight.js 동봉 (네트워크 불필요, 오프라인 동작)

전부 생성물이다 — 손으로 고치지 말고 원 워크스페이스의 문서를 갱신한 뒤 재생성해서 통째로 갈아끼운다.
정본은 caring_m 의 `wiki/` 와 각 저장소 README.

플랫폼 저장소 5개는 케어링 없는 형제 워크스페이스(`pk-caring/pl_2m`)와 공유한다. 그쪽 구조를 보려면
이 사이트에서 `cr_*` 만 빼고 읽으면 된다 — 의존은 케어링 → 플랫폼 한 방향뿐이라 나머지는 동일하다.
