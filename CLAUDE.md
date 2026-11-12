# 마음프로젝트 (mind-project)

"문화를 넘어 마음을 돌봅니다" — 마음프로젝트 소개 웹페이지 (한 페이지짜리 index.html).

- GitHub: https://github.com/sidd0262-ops/mind-project
- 파일: index.html 하나 (섹션: mission, programs, history, contact)
- 빌드 없음: 정적 페이지. 로컬 미리보기는 `python -m http.server 8765`
- 관련: 같은 이름의 조직 저장소 `maum-project/maum-project.github.io` 가 따로 있음 (어느 쪽이 실제 공개 사이트인지 작업 전에 사용자에게 확인)

## 진행 상황
- 2026-05-19 ~ 05-21: GitHub 웹에서 index.html 여러 차례 수정

## 내 프로젝트 생태계 (모든 저장소 공통)
GitHub 계정 `sidd0262-ops` 를 기준으로 Windows PC · Mac · 아이폰(클라우드 세션)에서 같은 코드를 씁니다.

| 저장소 | 내용 |
| --- | --- |
| Short-english | 쇼츠로 배우는 영어 회화 PWA (TypeScript, Render 배포) |
| coffee-log | 카페인 조절 기록지 PWA |
| psy-Cultural-adaptation | 문화적응 여정 PWA (Firebase) |
| timebox | 나만 쓰는 한지 타임박스 PWA |
| mind-project | 마음프로젝트 소개 페이지 |

- **폴더 위치:** Windows `Desktop\클로드 코드\` · Mac `~/Desktop/클로드 코드/` (폴더 이름은 저장소 이름과 달라도 됨)
- **한 번에 최신화:** Short-english 저장소의 `workspace/sync-all.ps1`(Windows) · `workspace/sync-all.sh`(Mac). 없는 저장소는 받고, 있는 저장소는 pull
- **작업 규칙**
  1. 시작 전 `git pull` (클라우드 세션은 항상 최신으로 시작)
  2. 끝나면 커밋하고 `git push` (사용자에게 확인 후). 로컬에만 두면 다른 기기에서 안 보임
  3. 같은 저장소를 두 기기에서 동시에 수정하지 않기
  4. API 키·비밀번호는 코드와 채팅에 쓰지 않기 (`.env`, 배포 서비스 환경변수 사용)
  5. 작업이 끝나면 이 파일의 "진행 상황"을 갱신해서 다음 기기·세션이 이어받게 하기
- 사용자와는 한국어로 대화
