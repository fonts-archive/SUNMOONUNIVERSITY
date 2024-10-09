# 선문대체

[배포처 바로가기](https://lily.sunmoon.ac.kr/Page2/About/SunmoonFont.aspx)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `SUNMOON UNIVERSITY`입니다.

### HTML

```html
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/gh/fonts-archive/SUNMOONUNIVERSITY/SUNMOONUNIVERSITY.css"
  type="text/css"
/>
```

### CSS `@Import`

```css
@import url("https://cdn.jsdelivr.net/gh/fonts-archive/SUNMOONUNIVERSITY/SUNMOONUNIVERSITY.css");
```

### CSS `@font-face`

```css
@font-face {
  font-family: 'SUNMOON UNIVERSITY';
  font-weight: normal;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/SUNMOONUNIVERSITY/SUNMOONUNIVERSITY.woff2') format('woff2'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/SUNMOONUNIVERSITY/SUNMOONUNIVERSITY.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/SUNMOONUNIVERSITY/SUNMOONUNIVERSITY.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link 
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/gh/fonts-archive/SUNMOONUNIVERSITY/subsets/SUNMOONUNIVERSITY-dynamic-subset.css"
  type="text/css"
/>
```

### CSS

```css
@import url("https://cdn.jsdelivr.net/gh/fonts-archive/SUNMOONUNIVERSITY/subsets/SUNMOONUNIVERSITY-dynamic-subset.css");
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.

```css
font-family: "SUNMOON UNIVERSITY", -apple-system, BlinkMacSystemFont, "Segoe UI",
  Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
※ 선문대학교 로고타입서체 '선문대체'는 미풍양속에 저해되거나, 학교 이미지를 손상시킬 수 있는 매체 등에 사용해서는 안 됨 
※ 해당 서체를 무단으로 변형하거나 상업적인 용도로의 배포/판매를 금지함 
※ 게재된 자료의 내용 또는 운영에 대한 개선 사항이 있을 시 콘텐츠 관리 담당자에게 연락하시기 바랍니다. 
- 콘텐츠 관리 담당 : 전산기획팀 / Tel : 041-530-2822
```
