# 세진사 대시보드 (프론트엔드)

세진사 내부 운영 대시보드의 **정적 프론트엔드**입니다. GitHub Pages로 게시됩니다.

- 사내 계정(@carwashlove.com / @sejinsa.co.kr) **Google 로그인**으로만 접근
- 이 저장소에는 **고객 개인정보(PII)나 비밀키, 데이터 쿼리 로직이 없습니다.**
  실데이터는 별도 **비공개 백엔드(Cloud Run)** 가 로그인 토큰을 검증한 뒤에만 제공합니다.

## 설정

`index.html` 상단 `CONFIG`:

| 항목 | 설명 |
|------|------|
| `GOOGLE_CLIENT_ID` | Google OAuth 2.0 클라이언트 ID (승인된 JS 원본에 이 Pages 주소 등록) |
| `API_BASE` | 백엔드(Cloud Run) URL. 배포 전에는 비워둠 |

> 백엔드 코드·배포는 비공개 저장소 `sejinsa-dashboard`에 있습니다.
