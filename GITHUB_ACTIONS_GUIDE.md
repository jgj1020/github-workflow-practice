# GitHub Actions 기본 사용 정리

## CI란?
코드를 push하거나 Pull Request를 만들었을 때
자동으로 코드 상태를 검사하는 과정이다.

## 이번에 만든 Workflow
- main 브랜치로 push할 때 실행
- main 브랜치 대상 Pull Request가 생성될 때 실행
- Node.js 20 환경 사용
- app.js 문법 검사
- status.js 문법 검사

## 확인 명령어

gh pr checks <PR번호>

## 성공 시
All checks were successful

## 실패 시
Actions 또는 PR의 Checks 탭에서
어떤 단계에서 실패했는지 확인할 수 있다.
