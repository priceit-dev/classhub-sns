# AGENTS.md — classhub-sns (SNS 마케팅)

클래스허브 SNS 마케팅. 콘텐츠 제작, 카피, 퍼널 분석.

## 작업 범위

- 콘텐츠 템플릿 작성
- 카피 생성 (구체적으로, 과장 금지)
- 숏폼 파이프라인 스크립트
- 마케팅 데이터 분석

## 개발 명령어

이 레포는 문서/콘텐츠 중심. 코드 프로젝트가 아님.

## 금지사항

- SNS 계정 직접 게시 금지 (초안 작성만)
- 고객 개인정보 포함 금지
- 가격/할인 정보 임의 생성 금지

## Codex 레포 규칙 로딩

- Codex는 세션 시작 시 `AGENTS.md`만 보지 말고 `CLAUDE.md`도 함께 읽는다.
- 이 레포의 역할, 세션 루틴, 금지사항, 구조 규칙은 `CLAUDE.md` 본문과 함께 해석한다.
- `AGENTS.md`는 Codex 진입점, `CLAUDE.md`는 프로젝트 규칙 본문으로 취급한다.

## Claude/Codex 공통 운영

- 이 레포는 `Claude Code`와 `Codex`를 동일한 절차로 운영한다.
- 두 도구 모두 전역 규칙과 이 레포 규칙을 함께 따른다.
- 새 기능, 구조 변경, 설계가 필요한 작업은 먼저 `brainstorming`으로 정리한다.
- 다단계 작업은 `writing-plans`로 계획을 먼저 만든다.
- 버그 수정과 이상 동작 분석은 먼저 `systematic-debugging`을 적용한다.
- 구현 변경은 가능하면 `test-driven-development` 기준으로 진행한다.
- 병렬 작업이 필요하면 `subagent-driven-development` 또는 `dispatching-parallel-agents`를 사용한다.
- 완료 선언, 커밋, PR 전에는 `verification-before-completion` 기준으로 검증한다.
- `AGENTS.md`와 `CLAUDE.md`는 항상 쌍으로 관리한다.
- 단, 이 문서의 프로젝트 제약과 금지사항이 `Superpowers`보다 우선한다.
