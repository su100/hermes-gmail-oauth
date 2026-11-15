# Hermes Gmail OAuth pages

개인용 Hermes Gmail 읽기 전용 OAuth 연결을 위한 공개 안내 페이지, 개인정보처리방침, 이용약관입니다.

## 공개 경로

- `/` — OAuth 애플리케이션 홈페이지
- `/privacy.html` — 개인정보처리방침
- `/terms.html` — 이용약관

## 배포 원칙

이 저장소는 `oauth.secret-blog.com` 전용으로 GitHub Pages에 배포합니다. `secret-blog.com`의 애플리케이션·메뉴·sitemap과 분리되어 있습니다.

Google OAuth 앱에는 다음 URL을 입력합니다.

- 애플리케이션 홈페이지: `https://oauth.secret-blog.com/`
- 개인정보처리방침: `https://oauth.secret-blog.com/privacy.html`
- 서비스 약관: `https://oauth.secret-blog.com/terms.html`

각 페이지는 공개 접근 가능해야 하지만, 일반 검색 노출을 줄이기 위해 `noindex, nofollow` 메타 태그를 사용합니다. 로그인 제한 또는 robots.txt 차단은 적용하지 않습니다.
