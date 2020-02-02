# 🌐 Spoqa Han Sans for Web

Spoqa 사에서 공개한 폰트인 `Spoqa Han Sans` 을 Google Fonts 방식으로 최적화 한 버전입니다.

## 👍 CDN

### JSDelivr (Recommended)

Raw 2.1.2 : <https://cdn.jsdelivr.net/gh/ddarkr/spoqa-han-sans-web@2.1.2/font.css>

Minified 2.1.2 : <https://cdn.jsdelivr.net/gh/ddarkr/spoqa-han-sans-web@2.1.2/font.min.css>

### RawCDN

Production (2.1.2) : <https://rawcdn.githack.com/ddarkr/spoqa-han-sans-web/05789fd1463f295e13dabb55f5e460b445e749b8/font.min.css>

## ⚠️ 주의사항

**`woff` 와 `woff2` 만 제공됩니다.**

- `woff` 기준으로, Internet Explorer는 9 이상부터 안드로이드 내장 브라우저는 안드로이드 버전 4.4부터 지원됩니다.
- 자세한 지원 브라우저는 [Can I Use](https://caniuse.com/#feat=woff) 를 참고하세요.

**`KR Subset` 버전을 기준으로 최적화되었습니다.**

- 따라서 **JP에 포함되어 있는 일본어와 KR Subset 이외의 글자들은 사용할 수 없습니다.**
- *Google Fonts Noto Sans KR CSS*를 기준으로 최적화되어, 일부 글자들은 누락되었을 수 있습니다.

## 컴파일

`node-sass` 패키지를 사용합니다.

```bash
node-sass font.scss font.css
node-sass font.scss font.min.css --output-style=compressed
```

## 기타

- `Spoqa Han Sans` 는 SIL Open Font License 로 배포됩니다. <https://github.com/spoqa/spoqa-han-sans>
- 기준이 된 CSS는 다음과 같습니다: <https://fonts.googleapis.com/css?family=Noto+Sans+KR>
- 참고한 최적화 방법: <https://sojin.io/article/%ED%95%9C%EA%B8%80-%EC%9B%B9-%ED%8F%B0%ED%8A%B8%EC%9D%98-%EC%B5%9C%EC%A0%81%ED%99%94/>
- 문제점이 있다면 PR 환영합니다 🤗
