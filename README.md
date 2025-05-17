# 팀 프로젝트 - Appointment App

## 브랜치 전략
- `main`: 배포용 (건드리지 않기)
- `dev`: 기능 병합용
- `feature/기능명`: 각자 작업용 브랜치

## 작업 순서
1. dev 브랜치에서 본인 작업 브랜치 생성
2. 작업 완료 후 PR 보내기
3. 리뷰 후 dev에 병합

## 예시
```bash
git checkout dev
git pull origin dev
git checkout -b feature/캘린더
