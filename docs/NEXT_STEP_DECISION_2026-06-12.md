# NEXT STEP DECISION — 2026-06-12

## 결론
지금 가장 먼저 할 일은 새 도구 공부가 아니라 **GitHub를 기준 원본으로 만들고, Drive/Claude Code/Copilot/Gemini를 그 주변 역할로 정렬하는 것**이다.

## 왜 이것이 1순위인가
현재 Google Drive에는 ARTIORA/ARTILANA 관련 제안서, 사업계획서, HTML 데모, 제출 가이드가 여러 버전으로 흩어져 있다. 이 상태에서 Claude Code, Copilot, Gemini를 더 붙이면 속도가 빨라지는 것이 아니라 서로 다른 파일을 기준으로 수정해서 더 헷갈린다.

## 오늘 기준 원본
- 프로젝트명: ARTILANA Lens
- 핵심 문장: IP 데이터 기반 창작물 권리위험·시각품질 진단 서비스
- 코드 기준 저장소: imkunghee/artiora
- 문서 기준: Drive의 최신 제출/사업계획서 자료를 GitHub docs로 요약 고정

## 도구 역할
- GitHub: 기준 원본, 코드, README, 결정 기록
- Google Drive: 제출본 PDF/PPT/HWP 보관소
- Claude Code: GitHub repo 안에서 코드 수정/정리 담당
- GitHub Copilot: VS Code 안에서 짧은 코드 자동완성 담당
- Gemini: 긴 문서/이미지/자료 비교용 보조 판단
- 본체 PC: 실제 개발·빌드·파일 정리 실행 장소

## 바로 다음 작업
1. `docs/project-source-of-truth.md` 작성
2. README에 현재 프로젝트 방향 5줄 추가
3. Drive의 최신 HTML 데모 1개만 골라 repo에 넣기
4. 나머지 후보 파일은 “archive / 참고”로 분리

## 하지 말 것
- Claude Code, Copilot, Gemini를 동시에 공부하지 않기
- 새 데모를 또 만들지 않기
- 이름을 ARTIORA/ARTILANA 사이에서 계속 흔들지 않기
- Drive 파일을 원본처럼 계속 복제하지 않기
