# GitHub 심화 연습 정리

## 전체 흐름

Issue
↓
Branch 생성
↓
파일 수정
↓
Commit
↓
Push
↓
Pull Request
↓
Review
↓
Request changes
↓
수정 → Commit → Push
↓
재검토 → Approve
↓
Squash Merge
↓
Issue 종료 + Branch 삭제

## 1. Issue 생성
- 작업 내용을 Issue로 등록
- 해야 할 작업을 명확하게 정리

## 2. Issue 기반 브랜치 생성
- gh issue develop 명령어 사용
- Issue 번호와 연결된 브랜치 생성

## 3. 파일 수정 및 Commit
- 작업 파일 수정
- git add
- git commit
- 변경 내용을 커밋 단위로 기록

## 4. Push
- git push
- 로컬 작업 내용을 GitHub 원격 저장소에 반영

## 5. Pull Request 생성
- gh pr create 사용
- Closes #이슈번호로 Issue 연결
- Merge 완료 시 Issue 자동 종료

## 6. Review
- 다른 계정으로 PR 검토
- Approve 또는 Request changes 사용

## 7. 수정 요청 대응
- Request changes 확인
- 코드 또는 문서 수정
- 다시 Commit 및 Push
- 기존 PR에 수정 내용 자동 반영

## 8. 재검토 및 승인
- 수정 내용 확인
- Approve 후 Submit review

## 9. Merge
- gh pr merge --squash --delete-branch
- Squash Merge 진행
- 작업 브랜치 삭제

## 배운 점

Issue를 기준으로 작업 브랜치를 만들고,
Pull Request를 통해 리뷰를 진행하는 전체 협업 흐름을 연습했다.

단순 승인뿐 아니라 수정 요청을 받은 뒤
내용을 수정하고 다시 Push한 후 재승인받는 과정도 진행했다.

또한 Squash Merge, Issue 자동 종료,
작업 브랜치 삭제 흐름까지 확인했다.
