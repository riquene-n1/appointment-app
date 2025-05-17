#팀 프로젝트 - Appointment App

---
## 브랜치 전략

- `main`: 배포용 (절대 직접 수정하지 않음)
- `dev`: 모든 기능을 병합하는 브랜치
- `feature/기능명`: 각자 기능별 작업용 브랜치 (예: `feature/alarm`)

---

## 기능별 디렉토리 구조

| 기능명     | 폴더 경로         | 담당자 (예시) |
|------------|-------------------|---------------|
| 알람       | `src/alarm/`      | 김상민 |
| 지도(최단경로) | `src/map/`        | 박노혁 |
| 채팅       | `src/chat/`       | 오성민 |

---

##  작업 순서

1. `dev` 브랜치에서 시작
2. 본인 작업 브랜치 생성
3. 작업 후 **GitHub에서 PR(Pull Request)** 생성
4. 팀장이 리뷰 후 `dev`에 병합

---

## 예시 명령어

```bash
git checkout dev
git pull origin dev
git checkout -b feature/alarm
# 작업 후
git add .
git commit -m "feat: 알람 기능 구현"
git push origin feature/alarm
