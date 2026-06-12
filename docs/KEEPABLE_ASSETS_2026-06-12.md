# KEEPABLE ASSETS — 2026-06-12

## 메모
사용자 표현: "키터블을 살릴 목록"

정확한 서비스명인지, 기존 Claude 프로젝트/아티팩트명인지, 혹은 "keepable = 살릴 수 있는 것"의 의미인지는 아직 확실하지 않다. 현재 프로젝트 맥락에서는 **ARTILANA에서 계속 살릴 자산 목록**으로 해석한다.

## 결론
지금 살릴 것은 새 기능 전체가 아니라, **돈을 받을 수 있는 최소 검수 흐름**이다.

최우선 상품 후보:

**ARTILANA Lens Mini Report**

- 입력: 이미지/캐릭터/포트폴리오 작업물 1장
- 출력: 권리위험 신호 + 공개 노출 위험 + 시각품질 피드백 1페이지 리포트
- 고객: 게임 원화가, 웹툰 작가, 포트폴리오 준비생, 소규모 스튜디오
- 가격 실험: 3만~10만원
- 목적: 기술 완성이 아니라, 고객이 돈을 낼 문제인지 검증

## 반드시 살릴 목록

### 1. ARTILANA Lens 포지셔닝
- IP 데이터 기반 창작물 권리위험·시각품질 진단 서비스
- 과장 금지: "완전한 도용 탐지"가 아니라 "위험 신호 분석 / 공개 노출 위험 추정 / 시각품질 검증"

### 2. Mini Report 상품
- 이미지 1장 단위 수동/반자동 검수
- 리포트 PDF 1장
- 유료 검증에 가장 가까운 형태

### 3. Checker Demo / Main Artspace HTML
- 데모 화면으로 활용 가능
- 지금은 기능 완성보다 "무엇을 해주는 서비스인지" 보여주는 용도

### 4. Watchdog / Evidence Console 아이디어
- 당장은 메인 상품이 아니라 보조 모듈
- 향후: 증거 리포트, 보호 레이어, 추적 가능성 설명에 사용

### 5. Drive 제출 자료
- 제출본 PDF/PPT는 보관
- 단, 원본 판단 기준은 GitHub docs로 이동

### 6. GitHub docs
- 결정 기록
- README
- 상품 정의
- 데모 구조
- Jira/Confluence로 보낼 작업 단위

## 보류할 목록

### 1. Style Marketplace
- 작가 스타일 API/LoRA 판매는 매력적이지만 법·계약·데이터 확보 문제가 크다.
- 지금 1순위가 아님.

### 2. 완전 자동 도용 탐지
- 기술·법적 리스크가 큼.
- 표현을 "위험 신호"로 낮춰야 안전하다.

### 3. 여러 AI 도구 동시 학습
- Claude Code, Copilot, Gemini, ComfyUI, Jira, Confluence를 동시에 배우면 실행력이 떨어진다.
- 먼저 GitHub 원본 구조를 고정한다.

## 버릴 가능성이 높은 것

### 1. 이름이 흔들리는 중복 자료
- ARTIORA / ARTILANA / Watchdog / ArtiSeal이 같은 의미로 섞인 중복본
- 아카이브로 보내고, 현재 기준은 ARTILANA Lens로 고정

### 2. 제출용으로만 만든 장식성 페이지
- 실제 고객 검증에 쓰이지 않으면 보류

## Jira / Confluence 연결 설계

### Confluence에 둘 것
- 프로젝트 개요
- 제품 정의
- 고객/시장 가설
- Mini Report 템플릿
- 회의록 / 결정 이유
- 제출자료 요약

### Jira에 둘 것
- 해야 할 일
- 버그
- 데모 수정
- 고객 인터뷰
- 리포트 샘플 제작
- 제출 마감 체크

### GitHub에 둘 것
- 코드
- HTML 데모
- README
- docs 원본 Markdown
- 결정 기록

## Jira 이슈로 쪼갤 첫 작업

1. README에 ARTILANA Lens 5줄 정의 추가
2. Mini Report PDF 목차 만들기
3. checker-demo.html 1개만 기준 데모로 선택
4. Drive 중복 데모 목록 정리
5. Confluence용 프로젝트 개요 페이지 작성
6. 첫 유료 테스트 고객 3명 후보 적기
7. Mini Report 샘플 1장 만들기

## 연결 판단

- GitHub ↔ Jira: 연결 가능. 커밋/브랜치/PR과 Jira 이슈를 연결하는 방식으로 운영 가능.
- Confluence ↔ Jira: 연결 가능. Confluence 문서에서 Jira 이슈를 표시하거나, Jira 작업의 배경 문서로 Confluence 페이지를 붙일 수 있다.
- GitHub ↔ Confluence: 직접/간접 연결 가능. 링크, Smart Link, 마켓플레이스 앱, 자동화 도구를 통해 연결한다.
- ChatGPT ↔ Jira/Confluence: Atlassian Rovo MCP/커넥터 계열을 통해 가능하지만, 계정 권한과 조직 설정이 필요하다.

## 오늘의 1순위

Jira/Confluence부터 세팅하지 말고, 먼저 GitHub docs에 원본 기준을 고정한다.

그 다음 순서:
1. GitHub README 고정
2. Mini Report 상품 정의
3. 데모 1개 선택
4. Confluence에 프로젝트 개요 복사
5. Jira에 첫 작업 7개 등록
