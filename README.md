# 🌐 Spoqa Han Sans for Web

Spoqa 사에서 공개한 폰트인 `Spoqa Han Sans` 을 Google Fonts 방식으로 최적화 한 버전입니다.

## ⚠️ 주의사항

**`woff` 와 `woff2` 만 제공됩니다.**

- `woff` 기준으로, Internet Explorer는 9 이상부터 안드로이드 내장 브라우저는 안드로이드 버전 4.4부터 지원됩니다.
- 자세한 지원 브라우저는 [Can I Use](https://caniuse.com/#feat=woff) 를 참고하세요.

## 컴파일

`node-sass` 패키지를 사용합니다.

```bash
node-sass font.scss font.css
node-sass font.scss font.min.css --output-style=compressed
```

## 기타

- 기준이 된 CSS는 다음과 같습니다: <https://fonts.googleapis.com/css?family=Noto+Sans+KR>
- 참고한 최적화 방법: <https://sojin.io/article/%ED%95%9C%EA%B8%80-%EC%9B%B9-%ED%8F%B0%ED%8A%B8%EC%9D%98-%EC%B5%9C%EC%A0%81%ED%99%94/>
- 로컬 서빙을 목적으로 만들어졌습니다. 문제점이 있다면 PR 환영합니다 🤗
