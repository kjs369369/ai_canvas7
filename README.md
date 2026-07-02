# AI캔버스 7기 랜딩페이지

AI캔버스 7기 모집/특강용 정적 HTML 랜딩페이지입니다.

## 현재 운영 페이지

| 구분 | 파일 | URL | 핵심 차이 |
|---|---|---|---|
| 기존 | `index.html` | `/` | 일반 모집, 얼리버드 2026.6.30 |
| 복제1 | `free-evening/index.html` | `/free-evening/` | 무료특강 2026.7.9(목) 오후 8:30, 얼리버드 2026.7.10 |
| 복제2 회원용 | `member-morning/index.html` | `/member-morning/` | 무료특강 2026.7.9(목) 오전 10:00, 얼리버드 2026.7.12, 회원 할인 안내 |

## 파일 구성

- 진입 파일: `index.html`
- 복제 페이지: `free-evening/index.html`, `member-morning/index.html`
- OG 이미지: `og.png`
- 정적 asset: `assets/`
- 운영 메모: `docs/landing-variants.md`

## 로컬 확인

```powershell
python -m http.server 8787 --bind 127.0.0.1
```

확인 URL:

- `http://127.0.0.1:8787/`
- `http://127.0.0.1:8787/free-evening/`
- `http://127.0.0.1:8787/member-morning/`
