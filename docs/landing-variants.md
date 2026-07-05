# AI캔버스 7기 랜딩 운영 구조

## 폴더 위치

- 로컬 작업 루트: `C:\project\lecture\Lecture summary\landing-sites\ai_canvas7`
- GitHub 원본: `https://github.com/kjs369369/ai_canvas7.git`
- Production 기준 URL: `https://ai-canvas7.vercel.app/`

## 페이지 구조

| 구분 | 로컬 파일 | 배포 URL | 용도 | 신청 링크 |
|---|---|---|---|---|
| 기존 | `index.html` | `/` | 기존 일반 모집 페이지 | `https://forms.gle/vCQyKPXGyGPRwaf89` |
| 무료특강 오후반 | `free-evening/index.html` | `/free-evening/` | 2026.7.9(목) 오후 8:30 무료특강 | `https://forms.gle/t8EBCayufpK4WX887` |
| 회원용 오전반 | `member-morning/index.html` | `/member-morning/` | 2026.7.9(목) 오전 10:00 회원용 무료특강 | `https://forms.gle/kXLPUULzuxeb32mA9` |

## 운영 원칙

- 같은 클래스 정보와 금액은 유지하고, 특강 일시·얼리버드 마감·신청 폼만 페이지별로 분리한다.
- GitHub repo는 하나로 유지하고, Vercel은 동일 프로젝트에서 하위 경로로 서빙한다.
- 새로 복제할 때는 `index.html`을 직접 덮어쓰지 말고 새 폴더를 만든 뒤 canonical, form URL, deadline JS를 함께 바꾼다.
