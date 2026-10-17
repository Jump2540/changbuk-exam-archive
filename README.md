# 창북중학교 2025학년도 2학기 기말고사 3학년 기출 보안 아카이브 (GitHub Pages)

## 주요 기능
- **기본 접속 상태 (`TOP SECRET` 기밀·블러 미리보기 모드)**:
  - 암호를 입력하지 않거나 틀린 암호를 입력하면 전 과목(국어·영어·수학·사회·역사·과학) 시험지의 핵심 지문·기하 도형·도표가 블러(Blur) 처리되고 주요 선지 및 NEIS 정답표가 `REDACTED` / `SECRET` 블랙바로 기밀 처리된 `TOP SECRET` 미리보기 버전이 표시됩니다.
- **암호 입력 시 (`careful`)**:
  - 상단 보안 암호창에 `careful`을 입력하고 **잠금 해제**를 누르면 즉시 **100% 원본 시험지(문제지 + 공식 NEIS 정답/배점표)**로 전환되며, `원본 클린` / `TOP SECRET 워터마크 원본` / `기밀·블러본` / `나란히 비교(Split View)` 모드를 자유롭게 전환할 수 있습니다.

## GitHub Pages 1분 배포 방법
1. GitHub에서 새 Public 저장소(Repository)를 생성합니다 (예: `changbuk-exam-archive`).
2. 본 압축 파일에 포함된 `index.html`과 `.nojekyll`(필요 시 `pdfs/` 폴더 포함)을 저장소 루트에 업로드(Commit)합니다.
3. 저장소의 **Settings -> Pages -> Build and deployment**에서 Branch를 `main` (`/root`)으로 설정하고 **Save**를 누르면 배포가 완료됩니다.
