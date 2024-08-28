# 프리젠테이션

[배포처 바로가기](https://freesentation.blog/)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `Freesentation`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/Freesentation/Freesentation.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/Freesentation/Freesentation.css');
```

### CSS `@font-face`

```css
@font-face {
  font-family: 'Freesentation';
  font-weight: 100;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/Freesentation/Freesentation-1Thin.woff2') format('woff2'),
       url('https://cdn.jsdelivr.net/gh/fonts-archive/Freesentation/Freesentation-1Thin.woff') format('woff'),
       url('https://cdn.jsdelivr.net/gh/fonts-archive/Freesentation/Freesentation-1Thin.otf') format('opentype'),
       url('https://cdn.jsdelivr.net/gh/fonts-archive/Freesentation/Freesentation-1Thin.ttf') format('truetype');
}
@font-face {
  font-family: 'Freesentation';
  font-weight: 200;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/Freesentation/Freesentation-2ExtraLight.woff2') format('woff2'),
       url('https://cdn.jsdelivr.net/gh/fonts-archive/Freesentation/Freesentation-2ExtraLight.woff') format('woff'),
       url('https://cdn.jsdelivr.net/gh/fonts-archive/Freesentation/Freesentation-2ExtraLight.otf') format('opentype'),
       url('https://cdn.jsdelivr.net/gh/fonts-archive/Freesentation/Freesentation-2ExtraLight.ttf') format('truetype');
}
@font-face {
  font-family: 'Freesentation';
  font-weight: 300;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/Freesentation/Freesentation-3Light.woff2') format('woff2'),
       url('https://cdn.jsdelivr.net/gh/fonts-archive/Freesentation/Freesentation-3Light.woff') format('woff'),
       url('https://cdn.jsdelivr.net/gh/fonts-archive/Freesentation/Freesentation-3Light.otf') format('opentype'),
       url('https://cdn.jsdelivr.net/gh/fonts-archive/Freesentation/Freesentation-3Light.ttf') format('truetype');
}
@font-face {
  font-family: 'Freesentation';
  font-weight: 400;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/Freesentation/Freesentation-4Regular.woff2') format('woff2'),
       url('https://cdn.jsdelivr.net/gh/fonts-archive/Freesentation/Freesentation-4Regular.woff') format('woff'),
       url('https://cdn.jsdelivr.net/gh/fonts-archive/Freesentation/Freesentation-4Regular.otf') format('opentype'),
       url('https://cdn.jsdelivr.net/gh/fonts-archive/Freesentation/Freesentation-4Regular.ttf') format('truetype');
}
@font-face {
  font-family: 'Freesentation';
  font-weight: 500;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/Freesentation/Freesentation-5Medium.woff2') format('woff2'),
       url('https://cdn.jsdelivr.net/gh/fonts-archive/Freesentation/Freesentation-5Medium.woff') format('woff'),
       url('https://cdn.jsdelivr.net/gh/fonts-archive/Freesentation/Freesentation-5Medium.otf') format('opentype'),
       url('https://cdn.jsdelivr.net/gh/fonts-archive/Freesentation/Freesentation-5Medium.ttf') format('truetype');
}
@font-face {
  font-family: 'Freesentation';
  font-weight: 600;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/Freesentation/Freesentation-6SemiBold.woff2') format('woff2'),
       url('https://cdn.jsdelivr.net/gh/fonts-archive/Freesentation/Freesentation-6SemiBold.woff') format('woff'),
       url('https://cdn.jsdelivr.net/gh/fonts-archive/Freesentation/Freesentation-6SemiBold.otf') format('opentype'),
       url('https://cdn.jsdelivr.net/gh/fonts-archive/Freesentation/Freesentation-6SemiBold.ttf') format('truetype');
}
@font-face {
  font-family: 'Freesentation';
  font-weight: 700;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/Freesentation/Freesentation-7Bold.woff2') format('woff2'),
       url('https://cdn.jsdelivr.net/gh/fonts-archive/Freesentation/Freesentation-7Bold.woff') format('woff'),
       url('https://cdn.jsdelivr.net/gh/fonts-archive/Freesentation/Freesentation-7Bold.otf') format('opentype'),
       url('https://cdn.jsdelivr.net/gh/fonts-archive/Freesentation/Freesentation-7Bold.ttf') format('truetype');
}
@font-face {
  font-family: 'Freesentation';
  font-weight: 800;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/Freesentation/Freesentation-8ExtraBold.woff2') format('woff2'),
       url('https://cdn.jsdelivr.net/gh/fonts-archive/Freesentation/Freesentation-8ExtraBold.woff') format('woff'),
       url('https://cdn.jsdelivr.net/gh/fonts-archive/Freesentation/Freesentation-8ExtraBold.otf') format('opentype'),
       url('https://cdn.jsdelivr.net/gh/fonts-archive/Freesentation/Freesentation-8ExtraBold.ttf') format('truetype');
}
@font-face {
  font-family: 'Freesentation';
  font-weight: 900;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/Freesentation/Freesentation-9Black.woff2') format('woff2'),
       url('https://cdn.jsdelivr.net/gh/fonts-archive/Freesentation/Freesentation-9Black.woff') format('woff'),
       url('https://cdn.jsdelivr.net/gh/fonts-archive/Freesentation/Freesentation-9Black.otf') format('opentype'),
       url('https://cdn.jsdelivr.net/gh/fonts-archive/Freesentation/Freesentation-9Black.ttf') format('truetype');
}
```

&nbsp;

## 가변 폰트(Variable Font)

일반적으로 폰트 파일은 "Regular", "Medium", "Bold" 등 여러 형태의 폰트가 별도의 파일로 제공되었습니다. 가변 폰트(Variable Font)는 이러한 단점을 해결하고자 하나의 파일에 여러 두께와 스타일을 담아 데이터 크기를 줄이고 강화된 커스터마이징 기능을 제공합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/Freesentation/variables/Freesentation-VF.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/Freesentation/variables/Freesentation-VF.css');
```

### CSS `@font-face`

```css
@font-face {
  font-family: 'Freesentation';
  font-weight: 1 999;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/Freesentation/variables/Freesentation-VF.ttf') format('truetype-variations');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/Freesentation/subsets/Freesentation-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/Freesentation/subsets/Freesentation-dynamic-subset.css');
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.


```css
font-family: "Freesentation", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
Freesentation은 노토산스(본고딕)와 같은 SIL 오픈폰트라이선스(OFL)에 따라
글꼴 단독 판매 또는 글꼴 라이선스 변경을 제외한 모든 상업적 행위 및 수정, 재배포가 가능합니다. 맘껏 쓰세요!
```
