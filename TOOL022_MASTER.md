# TOOL022 MASTER

## Canonical role
- Tool number: 22
- Historical conversation/file name: `22번 공통 준비물 도구`
- Purpose: 각 WIC 도구 개발에 공통으로 필요한 최소 준비물·표준 용어·기본 규칙·기본 흐름·공통 필드·샘플/입력 분류 기준을 정리하는 도구.

## Historical source-derived intent
- 파일 업로드 및 기본 정보 표시
- 공통 용어·규칙 출력
- 예전 도구의 개별 로직을 그대로 끌어오지 않고 현재 입력과 현재 화면을 기준으로 처리
- 자동 추론에 의존하지 않고 확인 가능한 입력과 표시 상태를 우선

## Current operating correction
- 이 도구를 이유로 WIC 전체 공통 구조를 선행 재개발하거나 전수조사하지 않는다.
- 공통화는 실제 다른 TOOL 작업에서 반복적으로 PASS된 구성요소가 생겼을 때만 점진적으로 승격한다.
- 현재 TOOL에 필요한 최소 준비물만 제공하고, 검증되지 않은 범용 엔진을 미리 만들지 않는다.

## Evidence and safety gates
- 과거 대화에서 '완전히 제거', '완성', '안전'이라고 표현된 내용은 실제 코드/파일/commit/검증 증거가 없으면 현재 완료 근거로 사용하지 않는다.
- 화면에 없는 정보나 과거 도구 정보를 현재 입력처럼 추론하지 않는다.
- 기존 PASS/VERIFIED/REMOTE_VERIFIED 공통 구성요소는 재개발·재검증하지 않는다.
- 새 변경 범위만 FIRST_VALIDATION 1회 수행한다.
- FULL_AUDIT / FULL_COMMONIZATION_AUDIT / REPEAT_WORK는 금지한다.

## Current historical catch-up state
- Historical feedback canonicalization: COMPLETE when this file and WIC_RULE_SOURCE pointer are committed and remote read-back succeeds.
- TOOL022 제품 개발 자체의 완료를 의미하지 않는다.
