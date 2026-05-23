# Just_website

JUST 동아리 웹사이트입니다. 빈티지한 영화 예고편 느낌의 스크롤 경험, 기수별 멤버 정리, 사이트 내 미니게임, 별도 상장관 페이지를 포함합니다.

## 실행

```sh
python3 -m http.server 5173
```

브라우저에서 `http://localhost:5173`을 엽니다.

## 구성

- `index.html`: 메인 랜딩, 성과 요약, 작품 분류, 미니게임, 멤버
- `awards.html`: 수상/상장 전용 페이지
- `app.js`: 스크롤 연출, 데이터 렌더링, 미니게임 동작
- `styles.css`: 빈티지 시네마 스타일
- `data/members.json`: 이름, 학번, 기수만 포함한 멤버 데이터
- `data/awards.json`: 수상 데이터
