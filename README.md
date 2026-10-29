# test-2
코디세이 2-2 문제로 테스트 결과

<!-- floe:start -->
## 계획 (Floe)

**국내 여행 추천 프로그램** — Floe의 여덟 단계로 만들어요.

- 기획서: [docs/PRD.md](docs/PRD.md)
- 결정 기록: [docs/decisions.md](docs/decisions.md)
- 1단계 무엇을 만들지 정하기: [docs/01-idea/idea.md](docs/01-idea/idea.md)
- 2단계 아이디어 적어 두기: [docs/02-plan/plan.md](docs/02-plan/plan.md)
- 3단계 꼭 필요한 기능 정리하기: [docs/03-requirements/requirements.md](docs/03-requirements/requirements.md)
- 4단계 만드는 방법 고르기: [docs/04-design/design.md](docs/04-design/design.md)
- 5단계 뼈대 먼저 이어 보기: [docs/05-skeleton/skeleton.md](docs/05-skeleton/skeleton.md)
- 6단계 하나씩 만들고 확인하기: [docs/06-build/build.md](docs/06-build/build.md)
- 단계 폴더 목차: [docs/README.md](docs/README.md)
<!-- floe:end -->

## 실행하는 법

```
python3 app.py 2026-11-15
```

- 예시 입력: `2026-11-15` (여행 날짜 하나만 받아요)
- 결과물: 추천 지역, 맛집, 1일 일정이 든 리포트가 화면(터미널)에 나와요.
- 웹 화면으로 보려면: `python3 app.py --serve` 를 켜고, 출력된 주소를 열어 날짜를 넣어요.
- 지금은 지역 추천(AI)과 맛집 찾기(지도)가 **자리표시 데이터**로 돌아요. 흐름만 이어 본 상태예요.

## 할 일

- [ ] AI 서비스로 지역 추천 받기 (`app.py`의 `recommend_region`)
- [ ] 지도 서비스로 맛집 찾기 (`app.py`의 `find_restaurants`)
- [ ] 열쇠를 `.env`에서 서버만 읽기 (`.env`는 `.gitignore`에 넣어 둠)
- [ ] 1일 일정을 AI 추천 · 맛집 결과로 채우기
- [ ] 화면 다듬기 (화면 원칙: 아직 모름)

## 정할 것

- 쓸 AI 서비스: (빈칸)
- 쓸 지도 서비스: (빈칸)
- 웹 서버 포트: (빈칸 — 지금은 빈 포트를 자동으로 골라요)
- 맛집 개수: (빈칸 — 기획서에 아직 모름)
- 리포트가 만들어지는 시간 기준: (빈칸)
