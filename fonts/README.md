## ⚠️ 배포 안내
현재 이 Repository에 올라가 있는 폰트는 웹 폰트로서 사용하기 위해 변환된 파일입니다.

긱블측의 LICENSE에 따라 원본 재배포가 불가하며, woff폰트로의 변환은 수정으로 간주하지 않아 업로드 한 것입니다.

가급적이면 본 Repository에서 사용하기 보다는, 직접 [긱블샵 (geekble.shop)](https://geekble.shop/shop_view/?idx=50)에서 폰트 이용 등록 후 otf 형태에서 사용하십시오.

라이센스는 [사용 가이드](../documentation/README.md)에서 확인하실 수 있습니다.<br /><br />

## 웹폰트 CDN (JSDelivr)
### HTML

```html
<link rel="stylesheet" as="style" crossorigin href="https://cdn.jsdelivr.net/gh/allpgs/geekblemalang@main/fonts/geekblemalang.css" />
```

### CSS

```css
@import url("https://cdn.jsdelivr.net/gh/allpgs/geekblemalang@main/fonts/GeekbleMalang.css");
```

### CSS 커스텀

```css
@font-face {
  font-family: 'GeekbleMalang';
  src: url('https://cdn.jsdelivr.net/gh/allpgs/geekblemalang@main/fonts/GeekbleMalang.woff2') format('woff2'), url('https://cdn.jsdelivr.net/gh/allpgs/geekblemalang@main/fonts/GeekbleMalang.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}
```
